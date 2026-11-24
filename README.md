UniLoop is a responsive, front-end web prototype for a campus-based car-sharing service, designed specifically for the Athens University of Economics and Business (AUEB) Patission campus. Built entirely with vanilla HTML, CSS, and JavaScript, it simulates the complete user journey of a modern mobility app without relying on external UI frameworks or mapping libraries.

The application demonstrates a polished, mobile-first user interface that transitions seamlessly to desktop environments. It allows users to discover available vehicles, filter by preferences, and experience a simulated reservation and driving flow.

Custom CSS Map Engine: An interactive, visually distinct map built entirely with CSS shapes, gradients, and absolute positioning, featuring recognizable campus landmarks (Main Building, Victoria Station, Pedion tou Areos).

Vehicle Discovery & Filtering: Users can search for specific cars or locations using the search bar (accessible via ⌘ K), and filter the fleet by "Electric" or "Available" (based on simulated battery levels).

Simulated Booking Flow: Includes a 10-minute reservation countdown timer, an active trip dashboard with live cost calculation, and up to 10 cumulative minutes of temporary parking per rental. During temporary parking the vehicle remains locked and assigned to the renter, billing continues, and a countdown shows the remaining allowance. The return flow gates completion on an allowed public-street parking selection, a required photo, a belongings checklist, and a simulated lock confirmation. Optional demo reward points show their star award and extra walking distance; the final demo receipt records the selected return details.

Return-flow limitation: The prototype has no live geofence, image review, vehicle lock, billing, account restriction, or appeal service. Parking selection and locking are simulated, and the photo is only checked for being an image file. The interface explicitly discloses these limitations; production enforcement and violation handling require trusted backend and vehicle-service integrations.

User Profile & Gamification: Tracks simulated ride history and total distance driven; awards +10 stars only when a demo reward point is selected during return.

Responsive Architecture: Adapts to any screen size, utilizing a side-panel layout on desktop and a native-feeling bottom-sheet/bottom-navigation paradigm on mobile devices.

Built-in Localization: Includes an internal dictionary structure supporting multiple languages, defaulting to Greek (el) for the local Athens market.
