<template>
  <button
    @click="openModal"
    :class="`event-block text-left h-15 text-white flex items-center overflow-hidden whitespace-nowrap ${widthClass} ${colorClass} ${colorHoverClass}`"
  >
    <div class="pl-4">
      <div class="font-semibold">{{ title }}</div>
      <div class="text-xs text-gray-200">{{ time }}</div>
    </div>
  </button>

  <TransitionRoot appear :show="isOpen" as="template">
    <Dialog as="div" @close="closeModal">
      <div class="fixed inset-0 z-10 overflow-y-auto">
        <div class="min-h-screen px-4 text-center">
          <TransitionChild
            as="template"
            enter="duration-300 ease-out"
            enter-from="opacity-0"
            enter-to="opacity-100"
            leave="duration-200 ease-in"
            leave-from="opacity-100"
            leave-to="opacity-0"
          >
            <DialogOverlay class="fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity" />
          </TransitionChild>

          <span class="inline-block h-screen align-middle" aria-hidden="true">
            &#8203;
          </span>

          <TransitionChild
            as="template"
            enter="duration-300 ease-out"
            enter-from="opacity-0 scale-95"
            enter-to="opacity-100 scale-100"
            leave="duration-200 ease-in"
            leave-from="opacity-100 scale-100"
            leave-to="opacity-0 scale-95"
          >
            <div
              :class="`bg-gray-900 text-white border-2 inline-block w-full max-w-md p-6 pr-16 my-8 overflow-hidden text-left align-middle transition-all transform shadow-xl rounded ${borderColorClass}`"
            >
              <button @click="closeModal" class="absolute top-3 right-3 hover:text-gray-400">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
              </button>
              <DialogTitle
                as="h3"
                :class="`text-2xl font-medium border-l-4 pl-3 ${borderColorClass}`"
              >
                {{ title }}
              </DialogTitle>
              <div class="mt-2">
                <p class="text-sm text-gray-200">{{ time }}</p>
                <p class="text-sm mt-4">
                  {{ description }}
                </p>
              </div>

              <div class="mt-4">
                <p class="text-sm text-gray-200" v-html="watchDescription"></p>
              </div>


            </div>
          </TransitionChild>
        </div>
      </div>
    </Dialog>
  </TransitionRoot>
</template>

<script>
import { ref } from 'vue'
import {
  TransitionRoot,
  TransitionChild,
  Dialog,
  DialogOverlay,
  DialogTitle,
} from '@headlessui/vue'

export default {
  props: ['title', 'time', 'description', 'widthClass', 'colorClass', 'colorHoverClass', 'borderColorClass', 'watchDescription'],

  components: {
    TransitionRoot,
    TransitionChild,
    Dialog,
    DialogOverlay,
    DialogTitle,
  },

  setup() {
    const isOpen = ref(false)

    return {
      isOpen,
      closeModal() {
        isOpen.value = false
      },
      openModal() {
        isOpen.value = true
      },
    }
  },
}
</script>

<style>

</style>
