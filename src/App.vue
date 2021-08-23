<template>
  <div class="container mx-auto px-4 xl:px-48 my-8">
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Numquam eius iure perspiciatis maxime voluptas itaque nulla praesentium? Totam architecto minima laborum dolorum quos ducimus et. Saepe dolores, aperiam in, dicta molestias non sequi dolorem pariatur perferendis dolor porro quibusdam tempore eligendi, quo illum necessitatibus iste assumenda voluptas voluptates labore quos?

    <TabGroup>
      <TabList>
        <Tab v-slot="{ selected }" as="template">
          <button
            class="font-semibold hover:bg-yellow-400 px-4 py-2"
            :class="[selected ? 'bg-yellow-500 text-white' : 'bg-white text-gray-900']"
          >
            Thursday, August 19
          </button>
        </Tab>
        <Tab v-slot="{ selected }" as="template">
          <button
            class="font-semibold hover:bg-yellow-400 px-4 py-2"
            :class="[selected ? 'bg-yellow-500 text-white' : 'bg-white text-gray-900']"
          >
            Friday, August 20
          </button>
        </Tab>
        <Tab v-slot="{ selected }" as="template">
          <button
            class="font-semibold hover:bg-yellow-400 px-4 py-2"
            :class="[selected ? 'bg-yellow-500 text-white' : 'bg-white text-gray-900']"
          >
            Saturday, August 21
          </button>
        </Tab>
        <Tab v-slot="{ selected }" as="template">
          <button
            class="font-semibold hover:bg-yellow-400 px-4 py-2"
            :class="[selected ? 'bg-yellow-500 text-white' : 'bg-white text-gray-900']"
          >
            Sunday, August 22
          </button>
        </Tab>

      </TabList>
      <TabPanels>
        <TabPanel>
          <div class="flex">
            <div class="w-40 bg-gray-900 text-white text-sm divide-y divide-white border-r border-white">
              <div class="h-10">&nbsp;</div>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Bethesda Global</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Bethesda Global</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Bethesda France</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Quakecon Community</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Quake Pro League</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
            </div>
            <div class="w-full bg-gray-500 divide-y divide-white overflow-x-auto overflow-y-hidden">
              <div class="h-10 bg-gray-900 text-white text-sm flex divide-x divide-white w-table">
                <div class="w-32 flex justify-center items-center">8:00 AM</div>
                <div class="w-32 flex justify-center items-center">8:30 AM</div>
                <div class="w-32 flex justify-center items-center">9:00 AM</div>
                <div class="w-32 flex justify-center items-center">9:30 AM</div>
                <div class="w-32 flex justify-center items-center">10:00 AM</div>
                <div class="w-32 flex justify-center items-center">10:30 AM</div>
                <div class="w-32 flex justify-center items-center">11:00 AM</div>
                <div class="w-32 flex justify-center items-center">11:30 AM</div>
                <div class="w-32 flex justify-center items-center">12:00 PM</div>
                <div class="w-32 flex justify-center items-center">12:30 PM</div>
                <div class="w-32 flex justify-center items-center">1:00 PM</div>
                <div class="w-32 flex justify-center items-center">1:30 PM</div>
                <div class="w-32 flex justify-center items-center">2:00 PM</div>
                <div class="w-32 flex justify-center items-center">2:30 PM</div>
                <div class="w-32 flex justify-center items-center">3:00 PM</div>
                <div class="w-32 flex justify-center items-center">3:30 PM</div>
                <div class="w-32 flex justify-center items-center">4:00 PM</div>
                <div class="w-32 flex justify-center items-center">4:30 PM</div>
                <div class="w-32 flex justify-center items-center">5:00 PM</div>
                <div class="w-32 flex justify-center items-center">5:30 PM</div>
              </div>
              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlot
                  title="Fallout 76 - UK Stream Team Build-a-thon"
                  time="8:00 AM EDT - 9:00 AM EDT"
                  description="The UK Stream Team race against the clock to see who can build the best C.A.M.P before the time runs out."
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />

                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="Let's talk Quake"
                  time="10:00 AM EDT - 11:00 AM EDT"
                  description="Quake is back, in this special stream John Linneman from Digital Foundry talks to Jerk Gustafsson of Machine Games about the title’s iconic legacy and what it meant to both of them."
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />

                <EventSlotEmpty />
                <EventSlotEmpty />
                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="DEATHLOOP Meets its Makers"
                  time="1:00 PM EDT - 2:00 PM EDT"
                  description="Step into the world of DEATHLOOP as we talk to Jason E. Kelley (Colt), Ozioma Akagha (Julianna), and the Arkane team about how they bring the game's main characters to life."
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />

                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="Exclusive Musical Performance by Trivium"
                  time="3:00 PM EDT - 4:00 PM EDT"
                  description="Heavy metal band Trivium will be streaming live to QuakeCon from the start of their 'Metal Tour of the Year!'"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />
              </div>

              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlotEmpty />
                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="Countdown / QuakeCon Warm Up"
                  time="9:30 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-32"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />

                <EventSlot
                  title="Bethesda Benelux Next Streamer:"
                  time="10:00 AM EDT - 12:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />

                <EventSlot
                  title="Interview with Arkane Lyon"
                  time="12:00 PM EDT - 12:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-32"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />

                <EventSlot
                  title="Cosplay Workshop & Catwalk"
                  time="12:30 PM EDT - 1:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />
              </div>
              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="QuakeCon Day 1 - Recap & Discussion with the Bethesda France Community Team"
                  time="9:00 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />

                <EventSlot
                  title="Cosplay Catch up & Conversation"
                  time="10:00 AM EDT - 11:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />

                <EventSlot
                  title="Fallout Lore Quiz"
                  time="11:00 AM EDT - 12:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />

                <EventSlot
                  title="All Things DEATHLOOP"
                  time="12:30 PM EDT - 2:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />
              </div>

              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlot
                  title="Good Morning QuakeCon"
                  time="8:00 AM EDT - 8:30 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-32"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="The Elder Scrolls Online - Lorecast Trivia"
                  time="9:00 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />


                <EventSlot
                  title="DOOM 2016 - Slayer Arcade Challenge"
                  time="10:00 AM EDT - 12:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="Fallout 76 - Junkashine Run Allstars Edition"
                  time="12:30 PM EDT - 2:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />

                <EventSlot
                  title="Quake Champions - Quick Draw 2v2 Finals"
                  time="2:00 PM EDT - 4:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />
              </div>
              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlot
                  title="Upper Bracket - Ro16"
                  time="8:00 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="Upper Bracket - Quarter Finals"
                  time="10:30 AM EDT - 12:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />

                <EventSlotEmpty />


                <EventSlot
                  title="Lower Brackets - Round 1"
                  time="12:30 AM EDT - 2:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="Lower Brackets - Round 2"
                  time="3:00 PM EDT - 4:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />
              </div>
            </div>
          </div>
        </TabPanel>
        <TabPanel>
          <div class="flex">
            <div class="w-40 bg-gray-900 text-white text-sm divide-y divide-white border-r border-white">
              <div class="h-10">&nbsp;</div>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Bethesda Global 2</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Bethesda Global</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Bethesda France</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Quakecon Community</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
              <a href="#" class="h-16 flex justify-between hover:text-gray-200 px-4 py-2">
                <span>Quake Pro League</span>
                <div class="pt-1">
                  <svg class="h-4 w-4" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path data-v-07bee6f7="" fill="currentColor" d="M391.17,103.47H352.54v109.7h38.63ZM285,103H246.37V212.75H285ZM120.83,0,24.31,91.42V420.58H140.14V512l96.53-91.42h77.25L487.69,256V0ZM449.07,237.75l-77.22,73.12H294.61l-67.6,64v-64H140.14V36.58H449.07Z" class=""></path></svg>
                </div>
              </a>
            </div>
            <div class="w-full bg-gray-500 divide-y divide-white overflow-x-auto overflow-y-hidden">
              <div class="h-10 bg-gray-900 text-white text-sm flex divide-x divide-white w-table">
                <div class="w-32 flex justify-center items-center">8:00 AM</div>
                <div class="w-32 flex justify-center items-center">8:30 AM</div>
                <div class="w-32 flex justify-center items-center">9:00 AM</div>
                <div class="w-32 flex justify-center items-center">9:30 AM</div>
                <div class="w-32 flex justify-center items-center">10:00 AM</div>
                <div class="w-32 flex justify-center items-center">10:30 AM</div>
                <div class="w-32 flex justify-center items-center">11:00 AM</div>
                <div class="w-32 flex justify-center items-center">11:30 AM</div>
                <div class="w-32 flex justify-center items-center">12:00 PM</div>
                <div class="w-32 flex justify-center items-center">12:30 PM</div>
                <div class="w-32 flex justify-center items-center">1:00 PM</div>
                <div class="w-32 flex justify-center items-center">1:30 PM</div>
                <div class="w-32 flex justify-center items-center">2:00 PM</div>
                <div class="w-32 flex justify-center items-center">2:30 PM</div>
                <div class="w-32 flex justify-center items-center">3:00 PM</div>
                <div class="w-32 flex justify-center items-center">3:30 PM</div>
                <div class="w-32 flex justify-center items-center">4:00 PM</div>
                <div class="w-32 flex justify-center items-center">4:30 PM</div>
                <div class="w-32 flex justify-center items-center">5:00 PM</div>
                <div class="w-32 flex justify-center items-center">5:30 PM</div>
              </div>
              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlot
                  title="Fallout 76 - UK Stream Team Build-a-thon"
                  time="8:00 AM EDT - 9:00 AM EDT"
                  description="The UK Stream Team race against the clock to see who can build the best C.A.M.P before the time runs out."
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />

                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="Let's talk Quake"
                  time="10:00 AM EDT - 11:00 AM EDT"
                  description="Quake is back, in this special stream John Linneman from Digital Foundry talks to Jerk Gustafsson of Machine Games about the title’s iconic legacy and what it meant to both of them."
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />

                <EventSlotEmpty />
                <EventSlotEmpty />
                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="DEATHLOOP Meets its Makers"
                  time="1:00 PM EDT - 2:00 PM EDT"
                  description="Step into the world of DEATHLOOP as we talk to Jason E. Kelley (Colt), Ozioma Akagha (Julianna), and the Arkane team about how they bring the game's main characters to life."
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />

                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="Exclusive Musical Performance by Trivium"
                  time="3:00 PM EDT - 4:00 PM EDT"
                  description="Heavy metal band Trivium will be streaming live to QuakeCon from the start of their 'Metal Tour of the Year!'"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-red-600"
                  colorHoverClass="hover:bg-red-700"
                  borderColorClass="border-red-600"
                />
              </div>

              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlotEmpty />
                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="Countdown / QuakeCon Warm Up"
                  time="9:30 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-32"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />

                <EventSlot
                  title="Bethesda Benelux Next Streamer:"
                  time="10:00 AM EDT - 12:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />

                <EventSlot
                  title="Interview with Arkane Lyon"
                  time="12:00 PM EDT - 12:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-32"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />

                <EventSlot
                  title="Cosplay Workshop & Catwalk"
                  time="12:30 PM EDT - 1:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-yellow-600"
                  colorHoverClass="hover:bg-yellow-800"
                  borderColorClass="border-yellow-600"
                />
              </div>
              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlotEmpty />
                <EventSlotEmpty />

                <EventSlot
                  title="QuakeCon Day 1 - Recap & Discussion with the Bethesda France Community Team"
                  time="9:00 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />

                <EventSlot
                  title="Cosplay Catch up & Conversation"
                  time="10:00 AM EDT - 11:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />

                <EventSlot
                  title="Fallout Lore Quiz"
                  time="11:00 AM EDT - 12:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />

                <EventSlot
                  title="All Things DEATHLOOP"
                  time="12:30 PM EDT - 2:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-blue-500"
                  colorHoverClass="hover:bg-blue-600"
                  borderColorClass="border-blue-600"
                />
              </div>

              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlot
                  title="Good Morning QuakeCon"
                  time="8:00 AM EDT - 8:30 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-32"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="The Elder Scrolls Online - Lorecast Trivia"
                  time="9:00 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-64"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />


                <EventSlot
                  title="DOOM 2016 - Slayer Arcade Challenge"
                  time="10:00 AM EDT - 12:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="Fallout 76 - Junkashine Run Allstars Edition"
                  time="12:30 PM EDT - 2:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />

                <EventSlot
                  title="Quake Champions - Quick Draw 2v2 Finals"
                  time="2:00 PM EDT - 4:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-indigo-600"
                  colorHoverClass="hover:bg-indigo-700"
                  borderColorClass="border-indigo-600"
                />
              </div>
              <div class="h-16 flex divide-x divide-white w-table">
                <EventSlot
                  title="Upper Bracket - Ro16"
                  time="8:00 AM EDT - 10:00 AM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="Upper Bracket - Quarter Finals"
                  time="10:30 AM EDT - 12:00 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />

                <EventSlotEmpty />


                <EventSlot
                  title="Lower Brackets - Round 1"
                  time="12:30 AM EDT - 2:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-128"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />

                <EventSlotEmpty />

                <EventSlot
                  title="Lower Brackets - Round 2"
                  time="3:00 PM EDT - 4:30 PM EDT"
                  description="Nam massa orci libero penatibus sit nec montes non at eros ante luctus curabitur rhoncus gravida dignissim metus mollis curae"
                  watchDescription="Watch on <a href='https://www.twitch.tv/bethesda' class='underline'>https://www.twitch.tv/bethesda</a>"
                  widthClass="w-96"
                  colorClass="bg-green-600"
                  colorHoverClass="hover:bg-green-700"
                  borderColorClass="border-green-600"
                />
              </div>
            </div>
          </div>
        </TabPanel>
        <TabPanel>Content 3</TabPanel>
        <TabPanel>Content 4</TabPanel>
      </TabPanels>
    </TabGroup>


  </div>
</template>

<script>
import EventSlot from './components/EventSlot.vue'
import EventSlotEmpty from './components/EventSlotEmpty.vue'
import { TabGroup, TabList, Tab, TabPanels, TabPanel } from '@headlessui/vue'


export default {
  components: {
    EventSlot,
    EventSlotEmpty,
    TabGroup,
    TabList,
    Tab,
    TabPanels,
    TabPanel,
  },
}
</script>

<style>

</style>
