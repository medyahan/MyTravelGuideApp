# MyTravelGuideApp

**MyTravelGuideApp** is a simple travel companion application that allows users to add and categorize their favorite places on a map. Users can add detailed information about a location, categorize it (e.g., Food, Museum, Park), and view it later on an interactive map. The app includes core functionality such as geolocation, Core Data persistence, and map integration.

---

## Features

- **Add Places**: Save places with details such as name, note, location, and category.
- **Category Management**: Categorize places with predefined categories like Food, Museum, etc.
- **Interactive Map**: Use long press to add location pins and view places on a map.
- **Segmentation View**: Filter places by category using a segmented control.
- **Details View**: View detailed information about a selected place, including navigation to the location using Apple Maps.
- **Data Persistence**: All data is saved using Core Data for local storage.
- **Dynamic UI**: Use pop-up buttons, action sheets, and segmented controls for a modern and intuitive user experience.
- **Keyboard Management**: Adjust views automatically when the keyboard is shown to ensure smooth text input.

---

## Technologies Used

- **UIKit**
- **MapKit**: For map and annotation handling.
- **CoreLocation**: For geolocation and user location updates.
- **CoreData**: For data persistence.
- **UIMenu & UIAction**: For category selection via pop-up buttons.
- **MKMapView**: For map display and user interaction.
- **UISegmentedControl**: For filtering and categorization.
  
---

## Screenshots

<p align="center">
    <img src="screenshots/home-screen-all-places.png" alt="Home Screen 1" width="200"/>
    <img src="screenshots/home-screen-categorized-places.png" alt="Home Screen 2" width="200"/>
    <img src="screenshots/home-screen-categorized-places-2.png" alt="Home Screen 3" width="200"/>
</p>
<p align="center">
    <img src="screenshots/add-place-screen.png" alt="Add Place Screen 1" width="200"/>
    <img src="screenshots/add-place-screen-2.png" alt="Add Place Screen 2" width="200"/>
    <img src="screenshots/details-screen.png" alt="Place Details" width="200"/>
</p>
<p align="center">
    <img src="screenshots/map-screen.png" alt="Map Screen" width="200"/>
</p>

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MyTravelGuideApp.git
