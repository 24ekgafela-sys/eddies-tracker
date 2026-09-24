<!DOCTYPE html>
<html lang="en" class="dark" id="html-root">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Gym, BJJ, Habit & Bulking Performance Suite</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    />
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              brand: "var(--color-brand)",
              "brand-hover": "var(--color-brand-hover)",
              "brand-light": "var(--color-brand-light)",
            },
          },
        },
      };
    </script>
    <style>
      :root {
        --color-brand: #3b82f6;
        --color-brand-hover: #2563eb;
        --color-brand-light: #dbeafe;
        --border-radius: 0.5rem;
      }

      .dynamic-rounded {
        border-radius: var(--border-radius) !important;
      }

      /* Custom Scrollbars */
      ::-webkit-scrollbar {
        width: 6px;
        height: 6px;
      }
      ::-webkit-scrollbar-track {
        background: rgba(0, 0, 0, 0.05);
      }
      ::-webkit-scrollbar-thumb {
        background: rgba(100, 116, 139, 0.4);
        border-radius: 4px;
      }

      .belt-sleeve {
        box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.5);
      }
    </style>
  </head>
  <body
    class="bg-slate-100 dark:bg-slate-900 text-slate-800 dark:text-slate-100 font-sans min-h-screen transition-colors duration-200"
  >
    <div id="app" class="min-h-screen flex flex-col md:flex-row">
      <aside
        class="w-full md:w-64 bg-slate-900 text-slate-300 flex-shrink-0 border-r border-slate-800 flex flex-col"
      >
        <div
          class="p-4 border-b border-slate-800 flex items-center justify-between"
        >
          <div class="flex items-center space-x-3">
            <div
              class="w-10 h-10 dynamic-rounded bg-brand flex items-center justify-center text-white font-bold text-xl shadow-lg"
            >
              <i class="fa-solid fa-fire"></i>
            </div>
            <div>
              <h1 class="font-bold text-slate-100 text-base leading-tight">
                PERFORMANCE
              </h1>
              <p class="text-xs text-slate-400">Habits, Gym, BJJ & Diet</p>
            </div>
          </div>
        </div>

        <!-- Tab Navigation Items -->
        <nav
          class="flex-1 p-3 space-y-1 overflow-y-auto flex md:flex-col horizontal-scroll md:horizontal-scroll-none space-x-1 md:space-x-0"
        >
          <button
            onclick="switchTab('dashboard')"
            id="nav-dashboard"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium transition-colors bg-brand text-white"
          >
            <i class="fa-solid fa-chart-pie w-5 text-center"></i>
            <span>Dashboard</span>
          </button>
          <button
            onclick="switchTab('habits')"
            id="nav-habits"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-circle-check w-5 text-center"></i>
            <span>Habits & Daily Tracker</span>
          </button>
          <button
            onclick="switchTab('belt')"
            id="nav-belt"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-award w-5 text-center"></i>
            <span>IBJJF Belt System</span>
          </button>
          <button
            onclick="switchTab('bjj')"
            id="nav-bjj"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-user-ninja w-5 text-center"></i>
            <span>Grappling Matrix</span>
          </button>
          <button
            onclick="switchTab('body')"
            id="nav-body"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-weight-scale w-5 text-center"></i>
            <span>Weight & Bulking</span>
          </button>
          <button
            onclick="switchTab('diet')"
            id="nav-diet"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-utensils w-5 text-center"></i>
            <span>Diet & Smart Meal</span>
          </button>
          <button
            onclick="switchTab('gym')"
            id="nav-gym"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-dumbbell w-5 text-center"></i>
            <span>Gym Strength</span>
          </button>
          <button
            onclick="switchTab('settings')"
            id="nav-settings"
            class="nav-btn w-full flex items-center space-x-3 px-3 py-2.5 dynamic-rounded text-sm font-medium hover:bg-slate-800 transition-colors"
          >
            <i class="fa-solid fa-sliders w-5 text-center"></i>
            <span>Theme & Studio</span>
          </button>
        </nav>

        <div
          class="p-3 border-t border-slate-800 bg-slate-950/50 flex items-center justify-between text-xs text-slate-400"
        >
          <div class="flex items-center space-x-2">
            <i class="fa-solid fa-circle text-emerald-500 text-[8px]"></i>
            <span id="sidebar-user-rank">Blue Belt • 2 Stripes</span>
          </div>
          <span id="sidebar-weight">82.5 kg</span>
        </div>
      </aside>

      <!-- Main Content Viewport -->
      <main class="flex-1 p-4 md:p-6 overflow-y-auto max-w-7xl mx-auto w-full">
        <div id="tab-dashboard" class="tab-content space-y-6">
          <!-- Top Summary Metrics Cards -->
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
            <div
              class="bg-white dark:bg-slate-800 p-4 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm flex items-center justify-between"
            >
              <div>
                <p class="text-xs font-semibold uppercase text-slate-400">
                  Current Rank
                </p>
                <h3
                  id="dash-rank-name"
                  class="text-lg font-bold text-slate-800 dark:text-slate-100"
                >
                  Blue Belt
                </h3>
                <p id="dash-rank-time" class="text-xs text-brand font-medium">
                  Eligible in 8 mos
                </p>
              </div>
              <div
                class="p-3 bg-brand-light dark:bg-slate-700 dynamic-rounded text-brand"
              >
                <i class="fa-solid fa-award text-2xl"></i>
              </div>
            </div>

            <div
              class="bg-white dark:bg-slate-800 p-4 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm flex items-center justify-between"
            >
              <div>
                <p class="text-xs font-semibold uppercase text-slate-400">
                  Weight & 30-Day Rate
                </p>
                <h3
                  id="dash-weight-val"
                  class="text-lg font-bold text-slate-800 dark:text-slate-100"
                >
                  82.5 kg
                </h3>
                <p
                  id="dash-weight-delta"
                  class="text-xs text-emerald-500 font-medium"
                >
                  +1.2 kg / 30d (Bulking)
                </p>
              </div>
              <div
                class="p-3 bg-emerald-100 dark:bg-slate-700 dynamic-rounded text-emerald-600 dark:text-emerald-400"
              >
                <i class="fa-solid fa-arrow-trend-up text-2xl"></i>
              </div>
            </div>

            <div
              class="bg-white dark:bg-slate-800 p-4 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm flex items-center justify-between"
            >
              <div>
                <p class="text-xs font-semibold uppercase text-slate-400">
                  Habit Completion
                </p>
                <h3
                  id="dash-habit-rate"
                  class="text-lg font-bold text-slate-800 dark:text-slate-100"
                >
                  4 / 5 Today
                </h3>
                <p class="text-xs text-amber-500 font-medium">
                  <i class="fa-solid fa-fire mr-1"></i>7 Day Streak!
                </p>
              </div>
              <div
                class="p-3 bg-amber-100 dark:bg-slate-700 dynamic-rounded text-amber-600 dark:text-amber-400"
              >
                <i class="fa-solid fa-circle-check text-2xl"></i>
              </div>
            </div>

            <div
              class="bg-white dark:bg-slate-800 p-4 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm flex items-center justify-between"
            >
              <div>
                <p class="text-xs font-semibold uppercase text-slate-400">
                  Daily Calorie Goal
                </p>
                <h3
                  id="dash-cal-target"
                  class="text-lg font-bold text-slate-800 dark:text-slate-100"
                >
                  2,850 kcal
                </h3>
                <p class="text-xs text-indigo-400 font-medium">
                  180g Protein Target
                </p>
              </div>
              <div
                class="p-3 bg-indigo-100 dark:bg-slate-700 dynamic-rounded text-indigo-600 dark:text-indigo-400"
              >
                <i class="fa-solid fa-utensils text-2xl"></i>
              </div>
            </div>
          </div>

          <!-- Middle Visualization Section -->
          <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
            <!-- Weight Trajectory Chart -->
            <div
              class="lg:col-span-2 bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <div class="flex items-center justify-between mb-4">
                <h3
                  class="font-bold text-slate-800 dark:text-slate-100 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-chart-line text-brand"></i>
                  <span>Bulking Trajectory & Weight Progress</span>
                </h3>
                <span
                  class="text-xs bg-slate-100 dark:bg-slate-700 text-slate-500 dark:text-slate-300 px-2.5 py-1 rounded-full"
                  >Target: 85.0 kg</span
                >
              </div>
              <div class="h-64 relative">
                <canvas id="dashWeightChart"></canvas>
              </div>
            </div>

            <!-- Submission Breakdown Chart -->
            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm flex flex-col justify-between"
            >
              <div>
                <h3
                  class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-crosshairs text-red-500"></i>
                  <span>Submission Ratio</span>
                </h3>
                <div class="h-48 relative flex items-center justify-center">
                  <canvas id="dashSubChart"></canvas>
                </div>
              </div>
              <div
                class="mt-4 pt-4 border-t border-slate-100 dark:border-slate-700 flex justify-around text-center text-xs"
              >
                <div>
                  <span class="block text-slate-400">Caught</span>
                  <span
                    id="dash-subs-caught"
                    class="font-bold text-emerald-500 text-base"
                    >42</span
                  >
                </div>
                <div
                  class="border-r border-slate-200 dark:border-slate-700"
                ></div>
                <div>
                  <span class="block text-slate-400">Tapped To</span>
                  <span
                    id="dash-subs-tapped"
                    class="font-bold text-red-500 text-base"
                    >18</span
                  >
                </div>
              </div>
            </div>
          </div>

          <!-- Habits Quick Panel & Gym PR Highlights -->
          <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <div class="flex items-center justify-between mb-4">
                <h3
                  class="font-bold text-slate-800 dark:text-slate-100 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-list-check text-amber-500"></i>
                  <span>Today's Habit Checklist</span>
                </h3>
                <button
                  onclick="switchTab('habits')"
                  class="text-xs text-brand hover:underline font-medium"
                >
                  Manage Habits
                </button>
              </div>
              <div id="dash-habit-list" class="space-y-2">
                <!-- Populated dynamically -->
              </div>
            </div>

            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <div class="flex items-center justify-between mb-4">
                <h3
                  class="font-bold text-slate-800 dark:text-slate-100 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-dumbbell text-indigo-500"></i>
                  <span>Recent Gym PRs & Sets</span>
                </h3>
                <button
                  onclick="switchTab('gym')"
                  class="text-xs text-brand hover:underline font-medium"
                >
                  Log Lift
                </button>
              </div>
              <div id="dash-gym-highlights" class="space-y-3">
                <!-- Populated dynamically -->
              </div>
            </div>
          </div>
        </div>

        <div id="tab-habits" class="tab-content hidden space-y-6">
          <div
            class="bg-white dark:bg-slate-800 p-6 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
          >
            <div
              class="flex flex-col sm:flex-row sm:items-center justify-between pb-4 border-b border-slate-200 dark:border-slate-700 gap-4 mb-4"
            >
              <div>
                <h2
                  class="text-xl font-bold text-slate-800 dark:text-slate-100 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-circle-check text-amber-500"></i>
                  <span>Daily Habit & Consistency Matrix</span>
                </h2>
                <p class="text-xs text-slate-400">
                  Track daily rituals, hydration, creatine, and protein
                  consistency.
                </p>
              </div>
              <button
                onclick="openAddHabitModal()"
                class="px-3.5 py-2 bg-brand text-white dynamic-rounded text-xs font-bold hover:bg-brand-hover flex items-center space-x-2"
              >
                <i class="fa-solid fa-plus"></i>
                <span>New Habit</span>
              </button>
            </div>

            <div id="habits-container" class="space-y-3">
              <!-- Dynamic Habits List -->
            </div>
          </div>
        </div>

        <div id="tab-belt" class="tab-content hidden space-y-6">
          <div
            class="bg-white dark:bg-slate-800 p-6 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
          >
            <div
              class="flex flex-col md:flex-row md:items-center justify-between pb-6 border-b border-slate-200 dark:border-slate-700 gap-4"
            >
              <div>
                <h2
                  class="text-xl font-bold text-slate-800 dark:text-slate-100 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-award text-yellow-500"></i>
                  <span>IBJJF Graduation System & Dynamic Belt Canvas</span>
                </h2>
                <p class="text-xs text-slate-400 mt-1">
                  Supports standard 4-degree adult belts & youth 12-stripe
                  custom gym configurations.
                </p>
              </div>
              <div class="flex items-center space-x-3">
                <label class="text-xs text-slate-400 font-medium"
                  >12-Stripe Youth System:</label
                >
                <input
                  type="checkbox"
                  id="belt-stripe-mode-toggle"
                  onchange="toggleStripeMode()"
                  class="w-4 h-4 text-brand rounded focus:ring-brand"
                />
              </div>
            </div>

            <!-- Dynamic Visual Belt Graphic Canvas -->
            <div
              class="my-8 py-8 px-4 bg-slate-950 rounded-xl flex flex-col items-center justify-center shadow-inner relative overflow-hidden"
            >
              <div
                class="text-xs font-mono text-slate-400 mb-4 tracking-widest uppercase"
                id="belt-graphic-label"
              >
                IBJJF Blue Belt • 2 Degrees
              </div>

              <!-- Belt Body Graphic Container -->
              <div
                class="w-full max-w-2xl h-16 bg-slate-800 rounded relative shadow-2xl flex items-center border border-slate-700 overflow-hidden"
                id="belt-container"
              >
                <div
                  id="belt-body-main"
                  class="h-full flex-1 relative flex items-center justify-end pr-20"
                >
                  <div
                    id="belt-youth-stripe"
                    class="w-full h-3 absolute top-1/2 -translate-y-1/2 hidden"
                  ></div>
                </div>

                <!-- Sleeve / Rank Bar -->
                <div
                  id="belt-sleeve-bar"
                  class="w-32 md:w-44 h-full bg-red-600 relative flex items-center justify-evenly px-2 belt-sleeve border-x-2 border-black/40"
                >
                  <div
                    id="sleeve-left-border"
                    class="absolute left-0 top-0 bottom-0 w-2 bg-white hidden"
                  ></div>
                  <div
                    id="sleeve-right-border"
                    class="absolute right-0 top-0 bottom-0 w-2 bg-white hidden"
                  ></div>

                  <div
                    id="belt-stripes-container"
                    class="flex items-center justify-evenly w-full h-full px-1"
                  >
                    <!-- Dynamic white stripes -->
                  </div>
                </div>

                <div
                  id="belt-body-tip"
                  class="w-12 h-full bg-slate-800 border-l border-black/30"
                ></div>
              </div>

              <div
                id="belt-status-badge"
                class="mt-4 inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-emerald-500/10 text-emerald-400 border border-emerald-500/20"
              >
                <i class="fa-solid fa-check-circle mr-1.5"></i> IBJJF Age &
                Minimum Time Period Satisfied
              </div>
            </div>

            <!-- Controls for Rank Selection -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
              <div>
                <label
                  class="block text-xs font-semibold text-slate-400 uppercase mb-2"
                  >Belt Rank Category</label
                >
                <select
                  id="belt-rank-select"
                  onchange="updateBeltSystem()"
                  class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2.5 text-sm font-medium focus:ring-2 focus:ring-brand"
                >
                  <optgroup label="Youth Belts (Ages 4-15)">
                    <option value="Y_WHITE">White Belt</option>
                    <option value="Y_WHITE_WHITE">White/White Belt</option>
                    <option value="Y_GREY_WHITE">Grey/White Belt</option>
                    <option value="Y_GREY">Grey Belt</option>
                    <option value="Y_GREY_BLACK">Grey/Black Belt</option>
                    <option value="Y_YELLOW_WHITE">Yellow/White Belt</option>
                    <option value="Y_YELLOW">Yellow Belt</option>
                    <option value="Y_YELLOW_BLACK">Yellow/Black Belt</option>
                    <option value="Y_ORANGE_WHITE">Orange/White Belt</option>
                    <option value="Y_ORANGE">Orange Belt</option>
                    <option value="Y_ORANGE_BLACK">Orange/Black Belt</option>
                    <option value="Y_GREEN_WHITE">Green/White Belt</option>
                    <option value="Y_GREEN">Green Belt</option>
                    <option value="Y_GREEN_BLACK">Green/Black Belt</option>
                  </optgroup>
                  <optgroup label="Adult Belts (Ages 16+)">
                    <option value="A_BLUE" selected>Blue Belt</option>
                    <option value="A_PURPLE">Purple Belt</option>
                    <option value="A_BROWN">Brown Belt</option>
                    <option value="A_BLACK">Black Belt</option>
                  </optgroup>
                  <optgroup label="Masters / Coral & Red (Degrees 7-9)">
                    <option value="M_RED_BLACK">
                      Red & Black Belt (7th Degree Coral)
                    </option>
                    <option value="M_RED_WHITE">
                      Red & White Belt (8th Degree Coral)
                    </option>
                    <option value="M_RED">
                      Red Belt (9th Degree Grand Master)
                    </option>
                  </optgroup>
                </select>
              </div>

              <div>
                <label
                  class="block text-xs font-semibold text-slate-400 uppercase mb-2"
                  >Degrees / Stripes (<span id="stripe-max-label">0 - 4</span
                  >)</label
                >
                <div class="flex items-center space-x-3">
                  <input
                    type="range"
                    id="belt-stripe-slider"
                    min="0"
                    max="4"
                    value="2"
                    oninput="updateBeltSystem()"
                    class="w-full accent-brand"
                  />
                  <span
                    id="stripe-count-display"
                    class="w-8 text-center font-bold text-lg text-brand"
                    >2</span
                  >
                </div>
              </div>

              <div>
                <label
                  class="block text-xs font-semibold text-slate-400 uppercase mb-2"
                  >Birth Year & Graduation Date</label
                >
                <div class="grid grid-cols-2 gap-2">
                  <input
                    type="number"
                    id="athlete-birth-year"
                    value="1998"
                    min="1930"
                    max="2026"
                    onchange="updateBeltSystem()"
                    class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-sm"
                  />
                  <input
                    type="date"
                    id="athlete-promo-date"
                    value="2023-06-15"
                    onchange="updateBeltSystem()"
                    class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-sm"
                  />
                </div>
              </div>
            </div>

            <!-- Minimum Time Rules Box -->
            <div
              class="mt-6 p-4 bg-slate-50 dark:bg-slate-700/50 dynamic-rounded border border-slate-200 dark:border-slate-600 grid grid-cols-1 md:grid-cols-3 gap-4 text-xs"
            >
              <div>
                <span class="text-slate-400 block font-medium"
                  >Calculated IBJJF Age:</span
                >
                <span
                  id="calc-athlete-age"
                  class="text-sm font-bold text-slate-700 dark:text-slate-200"
                  >28 Years Old</span
                >
              </div>
              <div>
                <span class="text-slate-400 block font-medium"
                  >Minimum Time Required:</span
                >
                <span id="calc-min-wait" class="text-sm font-bold text-brand"
                  >2.0 Years (24 Months)</span
                >
              </div>
              <div>
                <span class="text-slate-400 block font-medium"
                  >Next Eligible Rank Date:</span
                >
                <span
                  id="calc-eligible-date"
                  class="text-sm font-bold text-emerald-500"
                  >Eligible (June 15, 2025)</span
                >
              </div>
            </div>
          </div>
        </div>

        <div id="tab-bjj" class="tab-content hidden space-y-6">
          <div
            class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
          >
            <div
              class="flex flex-col md:flex-row md:items-center justify-between pb-4 border-b border-slate-200 dark:border-slate-700 gap-4 mb-4"
            >
              <div>
                <h3
                  class="font-bold text-slate-800 dark:text-slate-100 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-chess-knight text-brand"></i>
                  <span>Playstyle Archetype & Gameplan Sequences</span>
                </h3>
                <p class="text-xs text-slate-400">
                  Manage high-percentage tactical sequences and position
                  flowchains.
                </p>
              </div>
              <select
                id="playstyle-archetype"
                onchange="savePlaystyle()"
                class="bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs font-semibold"
              >
                <option value="guard">
                  Guard Retention & Inversion Specialist
                </option>
                <option value="pressure" selected>
                  Pressure Passer & Heavy Top Control
                </option>
                <option value="subhunter">Leg Lock & Submission Hunter</option>
                <option value="wrestler">
                  Scrapper / Wrestling & Takedown Heavy
                </option>
              </select>
            </div>

            <div class="space-y-4">
              <div class="flex items-center justify-between">
                <h4
                  class="text-sm font-bold text-slate-700 dark:text-slate-200"
                >
                  Constructed Gameplan Sequences
                </h4>
                <button
                  onclick="addSequence()"
                  class="px-3 py-1.5 bg-brand text-white dynamic-rounded text-xs font-medium hover:bg-brand-hover flex items-center space-x-1"
                >
                  <i class="fa-solid fa-plus"></i>
                  <span>Add Sequence</span>
                </button>
              </div>

              <div
                id="sequence-container"
                class="grid grid-cols-1 md:grid-cols-2 gap-4"
              >
                <!-- Populated dynamically -->
              </div>
            </div>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
            <!-- Submission Counters -->
            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <h3
                class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center justify-between"
              >
                <span
                  ><i class="fa-solid fa-bolt text-yellow-500 mr-2"></i>Log
                  Submission Finish</span
                >
              </h3>
              <form
                id="form-sub-log"
                onsubmit="logSubmission(event)"
                class="space-y-3"
              >
                <div class="grid grid-cols-2 gap-3">
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >Outcome</label
                    >
                    <select
                      id="sub-outcome"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                    >
                      <option value="CAUGHT">Caught (Executed)</option>
                      <option value="TAPPED">Tapped To (Given Up)</option>
                    </select>
                  </div>
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >Technique</label
                    >
                    <select
                      id="sub-technique"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                    >
                      <option value="Rear Naked Choke">Rear Naked Choke</option>
                      <option value="Armbar">Armbar</option>
                      <option value="Triangle Choke">Triangle Choke</option>
                      <option value="Heel Hook / Ankle Lock">
                        Heel Hook / Ankle Lock
                      </option>
                      <option value="Kimura / Americana">
                        Kimura / Americana
                      </option>
                      <option value="Guillotine">Guillotine</option>
                    </select>
                  </div>
                </div>
                <button
                  type="submit"
                  class="w-full py-2 bg-slate-900 dark:bg-slate-700 hover:bg-slate-800 text-white dynamic-rounded text-xs font-bold"
                >
                  Record Finish
                </button>
              </form>
            </div>

            <!-- Technique Roadmap -->
            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <div class="flex items-center justify-between mb-4">
                <h3 class="font-bold text-slate-800 dark:text-slate-100">
                  <i class="fa-solid fa-graduation-cap text-indigo-500 mr-2"></i
                  >Technique Roadmap
                </h3>
                <button
                  onclick="addRoadmapItem()"
                  class="text-xs text-brand hover:underline font-semibold"
                >
                  + Add Technique
                </button>
              </div>
              <div
                id="roadmap-full-list"
                class="space-y-2 max-h-60 overflow-y-auto pr-1"
              >
                <!-- Dynamic Roadmap -->
              </div>
            </div>
          </div>
        </div>

        <div id="tab-body" class="tab-content hidden space-y-6">
          <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <h3
                class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center space-x-2"
              >
                <i class="fa-solid fa-weight-scale text-brand"></i>
                <span>Log Body Weight</span>
              </h3>
              <form
                id="form-weight-log"
                onsubmit="logWeightMetric(event)"
                class="space-y-3"
              >
                <div>
                  <label class="block text-xs font-semibold text-slate-400 mb-1"
                    >Weight (kg)</label
                  >
                  <input
                    type="number"
                    step="0.1"
                    id="log-weight-val"
                    required
                    class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-sm"
                  />
                </div>
                <div class="grid grid-cols-2 gap-2">
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >Body Fat %</label
                    >
                    <input
                      type="number"
                      step="0.1"
                      id="log-bf-val"
                      placeholder="15.0"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-sm"
                    />
                  </div>
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >Muscle (kg)</label
                    >
                    <input
                      type="number"
                      step="0.1"
                      id="log-muscle-val"
                      placeholder="38.5"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-sm"
                    />
                  </div>
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-400 mb-1"
                    >Date</label
                  >
                  <input
                    type="date"
                    id="log-weight-date"
                    required
                    class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-sm"
                  />
                </div>
                <button
                  type="submit"
                  class="w-full py-2.5 bg-brand hover:bg-brand-hover text-white dynamic-rounded font-bold text-xs"
                >
                  Save Log
                </button>
              </form>
            </div>

            <div
              class="lg:col-span-2 bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm flex flex-col justify-between"
            >
              <div>
                <h3
                  class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center space-x-2"
                >
                  <i class="fa-solid fa-calculator text-emerald-500"></i>
                  <span>Bulking Rate Analytics</span>
                </h3>
                <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 mb-6">
                  <div
                    class="bg-slate-50 dark:bg-slate-700/50 p-3 dynamic-rounded border border-slate-200 dark:border-slate-600"
                  >
                    <span class="text-xs text-slate-400 block font-medium"
                      >Total Net Change</span
                    >
                    <span
                      id="delta-net-change"
                      class="text-xl font-bold text-emerald-500"
                      >+2.5 kg</span
                    >
                  </div>
                  <div
                    class="bg-slate-50 dark:bg-slate-700/50 p-3 dynamic-rounded border border-slate-200 dark:border-slate-600"
                  >
                    <span class="text-xs text-slate-400 block font-medium"
                      >7-Day Rate</span
                    >
                    <span
                      id="delta-7d-rate"
                      class="text-xl font-bold text-brand"
                      >+0.3 kg / wk</span
                    >
                  </div>
                  <div
                    class="bg-slate-50 dark:bg-slate-700/50 p-3 dynamic-rounded border border-slate-200 dark:border-slate-600"
                  >
                    <span class="text-xs text-slate-400 block font-medium"
                      >30-Day Rate</span
                    >
                    <span
                      id="delta-30d-rate"
                      class="text-xl font-bold text-indigo-500"
                      >+1.2 kg / mo</span
                    >
                  </div>
                </div>
              </div>

              <div class="overflow-x-auto">
                <table class="w-full text-left text-xs">
                  <thead
                    class="bg-slate-100 dark:bg-slate-700 text-slate-400 uppercase font-semibold"
                  >
                    <tr>
                      <th class="p-2">Date</th>
                      <th class="p-2">Weight</th>
                      <th class="p-2">Body Fat %</th>
                      <th class="p-2">Muscle Mass</th>
                      <th class="p-2 text-right">Action</th>
                    </tr>
                  </thead>
                  <tbody
                    id="weight-history-tbody"
                    class="divide-y divide-slate-100 dark:divide-slate-700"
                  >
                    <!-- Dynamic entries -->
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>

        <div id="tab-diet" class="tab-content hidden space-y-6">
          <div
            class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
          >
            <h3
              class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center space-x-2"
            >
              <i class="fa-solid fa-calculator text-amber-500"></i>
              <span>Smart TDEE & Bulking Macro Recommender</span>
            </h3>
            <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-4">
              <div>
                <label class="block text-xs font-semibold text-slate-400 mb-1"
                  >Goal Phase</label
                >
                <select
                  id="diet-goal-mode"
                  onchange="recalculateDietTargets()"
                  class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs font-medium"
                >
                  <option value="surplus" selected>
                    Lean Bulk (+350 kcal)
                  </option>
                  <option value="heavy_surplus">Heavy Bulk (+500 kcal)</option>
                  <option value="maintenance">Maintenance (0 kcal)</option>
                  <option value="cut">Cut (-400 kcal)</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-400 mb-1"
                  >Target Calories</label
                >
                <input
                  type="number"
                  id="diet-cal-input"
                  value="2850"
                  onchange="recalculateDietTargets()"
                  class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs font-bold"
                />
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-400 mb-1"
                  >Protein Target (g)</label
                >
                <input
                  type="number"
                  id="diet-protein-input"
                  value="180"
                  class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs font-bold text-amber-500"
                />
              </div>
              <div class="flex items-end">
                <button
                  onclick="generateSmartMealRecommendation()"
                  class="w-full py-2 bg-amber-500 hover:bg-amber-600 text-white dynamic-rounded font-bold text-xs flex items-center justify-center space-x-1 shadow"
                >
                  <i class="fa-solid fa-wand-magic-sparkles"></i>
                  <span>What Could I Eat?</span>
                </button>
              </div>
            </div>

            <div
              id="smart-meal-suggestion"
              class="hidden p-4 bg-amber-500/10 border border-amber-500/30 dynamic-rounded text-xs text-amber-900 dark:text-amber-200"
            >
              <!-- Dynamic generated meal recommendations -->
            </div>
          </div>
        </div>

        <div id="tab-gym" class="tab-content hidden space-y-6">
          <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
            <div
              class="bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <h3
                class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center space-x-2"
              >
                <i class="fa-solid fa-dumbbell text-brand"></i>
                <span>Log Strength Set</span>
              </h3>
              <form
                id="form-gym-log"
                onsubmit="logGymExercise(event)"
                class="space-y-3"
              >
                <div>
                  <label class="block text-xs font-semibold text-slate-400 mb-1"
                    >Exercise Name</label
                  >
                  <input
                    type="text"
                    id="gym-ex-name"
                    required
                    placeholder="Barbell Bench Press"
                    class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                  />
                </div>
                <div class="grid grid-cols-3 gap-2">
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >Weight (kg)</label
                    >
                    <input
                      type="number"
                      step="0.5"
                      id="gym-ex-weight"
                      required
                      placeholder="100"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                    />
                  </div>
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >Reps</label
                    >
                    <input
                      type="number"
                      id="gym-ex-reps"
                      required
                      placeholder="5"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                    />
                  </div>
                  <div>
                    <label
                      class="block text-xs font-semibold text-slate-400 mb-1"
                      >RPE (1-10)</label
                    >
                    <input
                      type="number"
                      step="0.5"
                      id="gym-ex-rpe"
                      placeholder="8.5"
                      class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                    />
                  </div>
                </div>
                <button
                  type="submit"
                  class="w-full py-2.5 bg-brand hover:bg-brand-hover text-white dynamic-rounded font-bold text-xs"
                >
                  Record Set & Calculate 1RM
                </button>
              </form>
            </div>

            <div
              class="lg:col-span-2 bg-white dark:bg-slate-800 p-5 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
            >
              <h3
                class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center justify-between"
              >
                <span>Logged Strength History & Est. 1RM</span>
                <span class="text-xs text-slate-400 font-normal"
                  >Formula: Weight × (1 + Reps/30)</span
                >
              </h3>
              <div class="overflow-x-auto">
                <table class="w-full text-left text-xs">
                  <thead
                    class="bg-slate-100 dark:bg-slate-700 text-slate-400 uppercase font-semibold"
                  >
                    <tr>
                      <th class="p-2">Exercise</th>
                      <th class="p-2">Load</th>
                      <th class="p-2">Reps</th>
                      <th class="p-2">RPE</th>
                      <th class="p-2">Est. 1RM</th>
                      <th class="p-2 text-right">Action</th>
                    </tr>
                  </thead>
                  <tbody
                    id="gym-history-tbody"
                    class="divide-y divide-slate-100 dark:divide-slate-700"
                  >
                    <!-- Dynamic gym logs -->
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>

        <div id="tab-settings" class="tab-content hidden space-y-6">
          <div
            class="bg-white dark:bg-slate-800 p-6 dynamic-rounded border border-slate-200 dark:border-slate-700 shadow-sm"
          >
            <h3
              class="font-bold text-slate-800 dark:text-slate-100 mb-4 flex items-center space-x-2"
            >
              <i class="fa-solid fa-palette text-brand"></i>
              <span>Customization Studio & Presets</span>
            </h3>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
              <div>
                <label class="block text-xs font-semibold text-slate-400 mb-2"
                  >Theme Preset</label
                >
                <div class="grid grid-cols-2 gap-2">
                  <button
                    onclick="setThemePreset('dark')"
                    class="p-3 border rounded-lg text-left text-xs font-semibold hover:border-brand"
                  >
                    Dark Slate
                  </button>
                  <button
                    onclick="setThemePreset('light')"
                    class="p-3 border rounded-lg text-left text-xs font-semibold hover:border-brand"
                  >
                    Clean Light
                  </button>
                  <button
                    onclick="setThemePreset('cyberpunk')"
                    class="p-3 border rounded-lg text-left text-xs font-semibold bg-purple-950 text-pink-400 border-pink-500"
                  >
                    Cyberpunk Neon
                  </button>
                  <button
                    onclick="setThemePreset('tactical')"
                    class="p-3 border rounded-lg text-left text-xs font-semibold bg-stone-900 text-emerald-400 border-emerald-600"
                  >
                    Tactical Green
                  </button>
                </div>
              </div>

              <div class="space-y-4">
                <div>
                  <label class="block text-xs font-semibold text-slate-400 mb-1"
                    >Custom Brand Accent Color</label
                  >
                  <input
                    type="color"
                    id="accent-color-picker"
                    value="#3b82f6"
                    onchange="updateCustomAccent(this.value)"
                    class="w-full h-10 dynamic-rounded cursor-pointer"
                  />
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-400 mb-1"
                    >Corner Radius Style</label
                  >
                  <select
                    onchange="updateBorderRadius(this.value)"
                    class="w-full bg-slate-50 dark:bg-slate-700 border border-slate-200 dark:border-slate-600 dynamic-rounded p-2 text-xs"
                  >
                    <option value="0.25rem">Sharp (4px)</option>
                    <option value="0.5rem" selected>Standard (8px)</option>
                    <option value="0.75rem">Rounded (12px)</option>
                    <option value="1rem">Pill (16px)</option>
                  </select>
                </div>
              </div>
            </div>

            <div
              class="pt-6 border-t border-slate-200 dark:border-slate-700 flex flex-wrap gap-3"
            >
              <button
                onclick="exportDataJSON()"
                class="px-4 py-2 bg-slate-900 dark:bg-slate-700 text-white dynamic-rounded text-xs font-bold flex items-center space-x-1"
              >
                <i class="fa-solid fa-download"></i>
                <span>Export All Data (JSON)</span>
              </button>
              <button
                onclick="document.getElementById('import-file-input').click()"
                class="px-4 py-2 bg-slate-100 dark:bg-slate-700 text-slate-700 dark:text-slate-200 dynamic-rounded text-xs font-bold flex items-center space-x-1"
              >
                <i class="fa-solid fa-upload"></i>
                <span>Import Backup</span>
              </button>
              <input
                type="file"
                id="import-file-input"
                class="hidden"
                onchange="importDataJSON(event)"
              />
              <button
                onclick="resetDataDefaults()"
                class="px-4 py-2 bg-red-500/10 text-red-500 dynamic-rounded text-xs font-bold hover:bg-red-500/20"
              >
                Reset Sample Data
              </button>
            </div>
          </div>
        </div>
      </main>
    </div>

    <script>
      const DEFAULT_DATA = {
        belt: {
          rank: "A_BLUE",
          stripes: 2,
          birthYear: 1998,
          promoDate: "2023-06-15",
          stripe12Mode: false,
        },
        habits: [
          {
            id: 1,
            name: "Creatine Monohydrate (5g)",
            streak: 12,
            completed: true,
          },
          { id: 2, name: "180g Protein Goal Hit", streak: 5, completed: true },
          { id: 3, name: "1 Gal Water Intake", streak: 8, completed: false },
          {
            id: 4,
            name: "BJJ Drilling / Mat Session",
            streak: 3,
            completed: true,
          },
          { id: 5, name: "8 Hours Sleep", streak: 4, completed: true },
        ],
        weightLogs: [
          { date: "2026-08-01", weight: 80.0, bf: 15.5, muscle: 37.5 },
          { date: "2026-08-15", weight: 81.2, bf: 15.6, muscle: 38.0 },
          { date: "2026-09-01", weight: 82.5, bf: 15.8, muscle: 38.4 },
        ],
        bjjStats: {
          matHours: 142.5,
          subsCaught: 42,
          subsTapped: 18,
          playstyle: "pressure",
          sequences: [
            {
              id: 1,
              name: "De La Riva Sweep Flow",
              flow: "DLR Hook -> Waiter Sweep -> Mount -> Cross Collar Choke",
              rating: "92%",
            },
          ],
          roadmap: [
            { id: 1, name: "Knee Cut Guard Pass", stage: "Mastered" },
            { id: 2, name: "Buggy Choke Counter", stage: "Drilling" },
          ],
        },
        gymLogs: [
          {
            id: 1,
            exercise: "Barbell Bench Press",
            weight: 100,
            reps: 5,
            rpe: 8.5,
            type: "Working Set",
          },
          {
            id: 2,
            exercise: "Back Squat",
            weight: 140,
            reps: 3,
            rpe: 9.0,
            type: "PR Attempt",
          },
        ],
        theme: {
          mode: "dark",
          accent: "#3b82f6",
          radius: "0.5rem",
        },
      };

      let appState =
        JSON.parse(localStorage.getItem("PERFORMANCE_SUITE_DATA_SUITE")) ||
        DEFAULT_DATA;
      let weightChartInstance = null;
      let subChartInstance = null;

      const IBJJF_BELTS = {
        Y_WHITE: {
          name: "White Belt",
          type: "youth",
          body: "#ffffff",
          sleeve: "#000000",
          youthStripe: null,
          minAge: 4,
          minWaitMonths: 0,
        },
        Y_WHITE_WHITE: {
          name: "White/White Belt",
          type: "youth",
          body: "#ffffff",
          sleeve: "#000000",
          youthStripe: "#ffffff",
          minAge: 4,
          minWaitMonths: 0,
        },
        Y_GREY_WHITE: {
          name: "Grey/White Belt",
          type: "youth",
          body: "#808080",
          sleeve: "#000000",
          youthStripe: "#ffffff",
          minAge: 4,
          minWaitMonths: 0,
        },
        Y_GREY: {
          name: "Grey Belt",
          type: "youth",
          body: "#808080",
          sleeve: "#000000",
          youthStripe: null,
          minAge: 4,
          minWaitMonths: 0,
        },
        Y_GREY_BLACK: {
          name: "Grey/Black Belt",
          type: "youth",
          body: "#808080",
          sleeve: "#000000",
          youthStripe: "#000000",
          minAge: 4,
          minWaitMonths: 0,
        },
        Y_YELLOW_WHITE: {
          name: "Yellow/White Belt",
          type: "youth",
          body: "#eab308",
          sleeve: "#000000",
          youthStripe: "#ffffff",
          minAge: 7,
          minWaitMonths: 0,
        },
        Y_YELLOW: {
          name: "Yellow Belt",
          type: "youth",
          body: "#eab308",
          sleeve: "#000000",
          youthStripe: null,
          minAge: 7,
          minWaitMonths: 0,
        },
        Y_YELLOW_BLACK: {
          name: "Yellow/Black Belt",
          type: "youth",
          body: "#eab308",
          sleeve: "#000000",
          youthStripe: "#000000",
          minAge: 7,
          minWaitMonths: 0,
        },
        Y_ORANGE_WHITE: {
          name: "Orange/White Belt",
          type: "youth",
          body: "#f97316",
          sleeve: "#000000",
          youthStripe: "#ffffff",
          minAge: 10,
          minWaitMonths: 0,
        },
        Y_ORANGE: {
          name: "Orange Belt",
          type: "youth",
          body: "#f97316",
          sleeve: "#000000",
          youthStripe: null,
          minAge: 10,
          minWaitMonths: 0,
        },
        Y_ORANGE_BLACK: {
          name: "Orange/Black Belt",
          type: "youth",
          body: "#f97316",
          sleeve: "#000000",
          youthStripe: "#000000",
          minAge: 10,
          minWaitMonths: 0,
        },
        Y_GREEN_WHITE: {
          name: "Green/White Belt",
          type: "youth",
          body: "#16a34a",
          sleeve: "#000000",
          youthStripe: "#ffffff",
          minAge: 13,
          minWaitMonths: 0,
        },
        Y_GREEN: {
          name: "Green Belt",
          type: "youth",
          body: "#16a34a",
          sleeve: "#000000",
          youthStripe: null,
          minAge: 13,
          minWaitMonths: 0,
        },
        Y_GREEN_BLACK: {
          name: "Green/Black Belt",
          type: "youth",
          body: "#16a34a",
          sleeve: "#000000",
          youthStripe: "#000000",
          minAge: 13,
          minWaitMonths: 0,
        },
        A_BLUE: {
          name: "Blue Belt",
          type: "adult",
          body: "#2563eb",
          sleeve: "#000000",
          minAge: 16,
          minWaitMonths: 24,
        },
        A_PURPLE: {
          name: "Purple Belt",
          type: "adult",
          body: "#7c3aed",
          sleeve: "#000000",
          minAge: 16,
          minWaitMonths: 18,
        },
        A_BROWN: {
          name: "Brown Belt",
          type: "adult",
          body: "#78350f",
          sleeve: "#000000",
          minAge: 18,
          minWaitMonths: 12,
        },
        A_BLACK: {
          name: "Black Belt",
          type: "adult",
          body: "#000000",
          sleeve: "#dc2626",
          minAge: 19,
          minWaitMonths: 36,
        },
        M_RED_BLACK: {
          name: "Red & Black Belt (7th Degree Coral)",
          type: "coral",
          body: "#dc2626",
          sleeve: "#000000",
          minAge: 50,
          minWaitMonths: 84,
        },
        M_RED_WHITE: {
          name: "Red & White Belt (8th Degree Coral)",
          type: "coral",
          body: "#dc2626",
          sleeve: "#ffffff",
          minAge: 57,
          minWaitMonths: 84,
        },
        M_RED: {
          name: "Red Belt (9th Degree Grand Master)",
          type: "grandmaster",
          body: "#dc2626",
          sleeve: "#000000",
          minAge: 67,
          minWaitMonths: 120,
        },
      };

      window.onload = function () {
        saveState();
        applyTheme();
        updateBeltSystem();
        renderDashboardCharts();
        renderAllTablesAndLists();
      };

      function saveState() {
        localStorage.setItem(
          "PERFORMANCE_SUITE_DATA_SUITE",
          JSON.stringify(appState)
        );
      }

      function switchTab(tabId) {
        document
          .querySelectorAll(".tab-content")
          .forEach((el) => el.classList.add("hidden"));
        document.querySelectorAll(".nav-btn").forEach((el) => {
          el.classList.remove("bg-brand", "text-white");
          el.classList.add("hover:bg-slate-800");
        });

        document.getElementById("tab-" + tabId).classList.remove("hidden");
        const activeBtn = document.getElementById("nav-" + tabId);
        if (activeBtn) {
          activeBtn.classList.add("bg-brand", "text-white");
        }
      }

      function toggleHabit(id) {
        const h = appState.habits.find((item) => item.id === id);
        if (h) {
          h.completed = !h.completed;
          if (h.completed) h.streak += 1;
          else h.streak = Math.max(0, h.streak - 1);
          saveState();
          renderAllTablesAndLists();
        }
      }

      function openAddHabitModal() {
        const name = prompt("Enter new habit name:");
        if (name) {
          appState.habits.push({
            id: Date.now(),
            name,
            streak: 0,
            completed: false,
          });
          saveState();
          renderAllTablesAndLists();
        }
      }

      function toggleStripeMode() {
        const is12 = document.getElementById("belt-stripe-mode-toggle").checked;
        appState.belt.stripe12Mode = is12;
        const slider = document.getElementById("belt-stripe-slider");
        slider.max = is12 ? 12 : 4;
        document.getElementById("stripe-max-label").innerText = is12
          ? "0 - 12"
          : "0 - 4";
        updateBeltSystem();
      }

      function updateBeltSystem() {
        const rankKey = document.getElementById("belt-rank-select").value;
        const count = parseInt(
          document.getElementById("belt-stripe-slider").value
        );
        const birthYear =
          parseInt(document.getElementById("athlete-birth-year").value) || 1998;
        const promoDateStr =
          document.getElementById("athlete-promo-date").value || "2023-06-15";

        appState.belt.rank = rankKey;
        appState.belt.stripes = count;
        appState.belt.birthYear = birthYear;
        appState.belt.promoDate = promoDateStr;
        saveState();

        document.getElementById("stripe-count-display").innerText = count;
        const beltData = IBJJF_BELTS[rankKey];

        const bodyEl = document.getElementById("belt-body-main");
        const sleeveEl = document.getElementById("belt-sleeve-bar");
        const youthStripeEl = document.getElementById("belt-youth-stripe");
        const stripesContainer = document.getElementById(
          "belt-stripes-container"
        );

        bodyEl.style.backgroundColor = beltData.body;
        sleeveEl.style.backgroundColor = beltData.sleeve;

        if (beltData.youthStripe) {
          youthStripeEl.classList.remove("hidden");
          youthStripeEl.style.backgroundColor = beltData.youthStripe;
        } else {
          youthStripeEl.classList.add("hidden");
        }

        stripesContainer.innerHTML = "";
        for (let i = 0; i < count; i++) {
          const stripe = document.createElement("div");
          stripe.className = "w-1.5 h-full bg-white rounded-xs shadow";
          stripesContainer.appendChild(stripe);
        }

        document.getElementById("belt-graphic-label").innerText = `IBJJF ${
          beltData.name
        } • ${count} ${count === 1 ? "Degree" : "Degrees"}`;

        const currentYear = new Date().getFullYear();
        const athleteAge = currentYear - birthYear;
        document.getElementById(
          "calc-athlete-age"
        ).innerText = `${athleteAge} Years Old`;

        const promoDate = new Date(promoDateStr);
        const eligibleDate = new Date(promoDate);
        eligibleDate.setMonth(eligibleDate.getMonth() + beltData.minWaitMonths);

        const now = new Date();
        const isAgeEligible = athleteAge >= beltData.minAge;
        const isTimeEligible = now >= eligibleDate;

        document.getElementById("calc-min-wait").innerText = `${(
          beltData.minWaitMonths / 12
        ).toFixed(1)} Years (${beltData.minWaitMonths} Months)`;

        const badge = document.getElementById("belt-status-badge");
        if (isAgeEligible && isTimeEligible) {
          badge.className =
            "mt-4 inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-emerald-500/10 text-emerald-400 border border-emerald-500/20";
          badge.innerHTML = `<i class="fa-solid fa-check-circle mr-1.5"></i> IBJJF Age & Minimum Time Satisfied`;
          document.getElementById(
            "calc-eligible-date"
          ).innerText = `Eligible (${eligibleDate.toLocaleDateString()})`;
        } else {
          badge.className =
            "mt-4 inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-amber-500/10 text-amber-400 border border-amber-500/20";
          badge.innerHTML = `<i class="fa-solid fa-clock mr-1.5"></i> Minimum Wait / Age Pending`;
          document.getElementById(
            "calc-eligible-date"
          ).innerText = `Eligible on ${eligibleDate.toLocaleDateString()}`;
        }

        document.getElementById(
          "sidebar-user-rank"
        ).innerText = `${beltData.name.replace(
          " Belt",
          ""
        )} • ${count} Stripes`;
        document.getElementById("dash-rank-name").innerText = beltData.name;
      }

      function renderDashboardCharts() {
        const ctxWeight = document
          .getElementById("dashWeightChart")
          .getContext("2d");
        const dates = appState.weightLogs.map((l) => l.date);
        const weights = appState.weightLogs.map((l) => l.weight);

        if (weightChartInstance) weightChartInstance.destroy();
        weightChartInstance = new Chart(ctxWeight, {
          type: "line",
          data: {
            labels: dates,
            datasets: [
              {
                label: "Body Weight (kg)",
                data: weights,
                borderColor: "#3b82f6",
                backgroundColor: "rgba(59, 130, 246, 0.1)",
                fill: true,
                tension: 0.3,
              },
            ],
          },
          options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: { legend: { display: false } },
            scales: {
              y: { grid: { color: "rgba(250,250,250,0.05)" } },
              x: { grid: { display: false } },
            },
          },
        });

        const ctxSub = document.getElementById("dashSubChart").getContext("2d");
        if (subChartInstance) subChartInstance.destroy();
        subChartInstance = new Chart(ctxSub, {
          type: "doughnut",
          data: {
            labels: ["Caught", "Tapped To"],
            datasets: [
              {
                data: [
                  appState.bjjStats.subsCaught,
                  appState.bjjStats.subsTapped,
                ],
                backgroundColor: ["#10b981", "#ef4444"],
              },
            ],
          },
          options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: { legend: { position: "bottom" } },
          },
        });
      }

      function logGymExercise(e) {
        e.preventDefault();
        const exName = document.getElementById("gym-ex-name").value;
        const weight = parseFloat(
          document.getElementById("gym-ex-weight").value
        );
        const reps = parseInt(document.getElementById("gym-ex-reps").value);
        const rpe =
          parseFloat(document.getElementById("gym-ex-rpe").value) || 8.0;

        const newEntry = {
          id: Date.now(),
          exercise: exName,
          weight,
          reps,
          rpe,
        };
        appState.gymLogs.unshift(newEntry);
        saveState();
        renderAllTablesAndLists();
        document.getElementById("form-gym-log").reset();
      }

      function logWeightMetric(e) {
        e.preventDefault();
        const weight = parseFloat(
          document.getElementById("log-weight-val").value
        );
        const bf = parseFloat(document.getElementById("log-bf-val").value) || 0;
        const muscle =
          parseFloat(document.getElementById("log-muscle-val").value) || 0;
        const date = document.getElementById("log-weight-date").value;

        appState.weightLogs.push({ date, weight, bf, muscle });
        appState.weightLogs.sort((a, b) => new Date(a.date) - new Date(b.date));
        saveState();
        renderDashboardCharts();
        renderAllTablesAndLists();
      }

      function generateSmartMealRecommendation() {
        const el = document.getElementById("smart-meal-suggestion");
        el.classList.remove("hidden");
        el.innerHTML = `
                <div class="font-bold text-sm mb-1"><i class="fa-solid fa-utensils mr-1"></i> Clean Bulking Meal Idea:</div>
                <p><strong>Option:</strong> 250g Lean Ground Turkey / Beef + 1.5 Cups Jasmine Rice + Half Avocado + Olive Oil drizzled.</p>
                <p class="mt-1 font-mono text-[11px]">Macros: ~780 kcal | 52g Protein | 82g Carbs | 24g Fats</p>
            `;
      }

      function renderAllTablesAndLists() {
        // Habits List Render
        const habitsContainer = document.getElementById("habits-container");
        const dashHabitsList = document.getElementById("dash-habit-list");
        habitsContainer.innerHTML = "";
        dashHabitsList.innerHTML = "";

        appState.habits.forEach((h) => {
          const item = document.createElement("div");
          item.className =
            "p-3 bg-slate-50 dark:bg-slate-700/50 dynamic-rounded border border-slate-200 dark:border-slate-600 flex items-center justify-between";
          item.innerHTML = `
                    <div class="flex items-center space-x-3">
                        <button onclick="toggleHabit(${
                          h.id
                        })" class="w-6 h-6 rounded flex items-center justify-center border ${
            h.completed
              ? "bg-emerald-500 border-emerald-500 text-white"
              : "border-slate-400"
          }">
                            ${
                              h.completed
                                ? '<i class="fa-solid fa-check text-xs"></i>'
                                : ""
                            }
                        </button>
                        <span class="text-xs font-semibold ${
                          h.completed ? "line-through text-slate-400" : ""
                        }">${h.name}</span>
                    </div>
                    <span class="text-xs font-bold text-amber-500"><i class="fa-solid fa-fire mr-1"></i>${
                      h.streak
                    }d Streak</span>
                `;
          habitsContainer.appendChild(item);

          const dashItem = item.cloneNode(true);
          dashHabitsList.appendChild(dashItem);
        });

        // Gym Table
        const gymBody = document.getElementById("gym-history-tbody");
        gymBody.innerHTML = "";
        appState.gymLogs.forEach((log) => {
          const est1RM = (log.weight * (1 + log.reps / 30)).toFixed(1);
          const tr = document.createElement("tr");
          tr.className = "hover:bg-slate-50 dark:hover:bg-slate-700/50";
          tr.innerHTML = `
                    <td class="p-2 font-bold">${log.exercise}</td>
                    <td class="p-2">${log.weight} kg</td>
                    <td class="p-2">${log.reps}</td>
                    <td class="p-2">${log.rpe}</td>
                    <td class="p-2 text-brand font-bold">${est1RM} kg</td>
                    <td class="p-2 text-right"><button onclick="deleteGymLog(${log.id})" class="text-red-400 hover:text-red-600"><i class="fa-solid fa-trash"></i></button></td>
                `;
          gymBody.appendChild(tr);
        });

        // Weight History Table
        const weightBody = document.getElementById("weight-history-tbody");
        weightBody.innerHTML = "";
        appState.weightLogs.forEach((w, idx) => {
          const tr = document.createElement("tr");
          tr.className = "hover:bg-slate-50 dark:hover:bg-slate-700/50";
          tr.innerHTML = `
                    <td class="p-2 font-medium">${w.date}</td>
                    <td class="p-2 font-bold text-brand">${w.weight} kg</td>
                    <td class="p-2">${w.bf ? w.bf + "%" : "--"}</td>
                    <td class="p-2">${w.muscle ? w.muscle + " kg" : "--"}</td>
                    <td class="p-2 text-right"><button onclick="deleteWeightLog(${idx})" class="text-red-400 hover:text-red-600"><i class="fa-solid fa-trash"></i></button></td>
                `;
          weightBody.appendChild(tr);
        });
      }

      function deleteGymLog(id) {
        appState.gymLogs = appState.gymLogs.filter((l) => l.id !== id);
        saveState();
        renderAllTablesAndLists();
      }

      function deleteWeightLog(idx) {
        appState.weightLogs.splice(idx, 1);
        saveState();
        renderDashboardCharts();
        renderAllTablesAndLists();
      }

      function setThemePreset(preset) {
        appState.theme.mode = preset;
        saveState();
        applyTheme();
      }

      function applyTheme() {
        const root = document.documentElement;
        if (
          appState.theme.mode === "dark" ||
          appState.theme.mode === "cyberpunk" ||
          appState.theme.mode === "tactical"
        ) {
          root.classList.add("dark");
        } else {
          root.classList.remove("dark");
        }
      }

      function exportDataJSON() {
        const str =
          "data:text/json;charset=utf-8," +
          encodeURIComponent(JSON.stringify(appState, null, 2));
        const anchor = document.createElement("a");
        anchor.setAttribute("href", str);
        anchor.setAttribute("download", "performance_suite_data.json");
        document.body.appendChild(anchor);
        anchor.click();
        anchor.remove();
      }

      function importDataJSON(e) {
        const file = e.target.files[0];
        if (!file) return;
        const reader = new FileReader();
        reader.onload = function (evt) {
          try {
            appState = JSON.parse(evt.target.result);
            saveState();
            location.reload();
          } catch (err) {
            alert("Invalid JSON file");
          }
        };
        reader.readAsText(file);
      }
    </script>
  </body>
</html>
