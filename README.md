![Banner](/pictures/banner.png)
# ECE297 Maps Project 
![GitHubStats](/pictures/githubStats1.png)<br/>
A map application written in C++ from a very low level API reading from an OpenStreetMaps database<br/>
Note: because this was a University project, the source code is not and will not be public
## Features
### Technical Features
* Read data from Open Street Map database (subways)
* Navigation route calculations between 2 points 
* Navigation routes for a Car and a combination of Car and Walking
* Dijkstra's Algorithm with A* search implementation
* Multi-start path finding optimizations
* Travelling Salesman problem (given start, end position, must go to pickup stations and drop-off stations with specific carrying capacity in the most efficient way)solved using a Greedy Algorithm with Multi-Destination Dijkstra
* Using multi-threading optimizations within cycles to improve delivery time
* Employed iterative improvement algorithms, Intersection swap and 2-opt
### Visual Features
* Display points of interests
* Display subway stops
* Display one way streets
* Dark mode following WCAG contrast guidelines
* Dynamic street names (only show one street name on the screen at a time)
* Street names stay on the screen
* Dynamic loading of various visual elements based on zoom level
* High detail mode, smoothing out jagged road edges
* Distinction between main roads and non-main roads
* Distinction between geographic features such as water, parks, beaches, etc.
### User Interface and Interaction Features
* Intuitive map selection
* Drop-down menu for suggestion to search
* Autocomplete of search if partially filled in
* Splash loading screen
* Ability to toggle information: Dark mode, one way streets, subway stops, points of interest
* Points of interest categorized and shown with custom icons
* Zooming in/out
* Panning around
* Search for a point of interest and locate on map
* Search for a street intersection and locate on map
* Click to get details about specific intersections
* Help text menu
* Error dialog popups
* Status bar with information and instructions of usage
* Can start/end navigation route at searched intersection
* Can start/end navigation route at searched point of interest
* Change navigation parameters, such as ```Turning Penalty```, ```Walking Speed```,```Walking Limit```
* Set different navigation types: ```Car``` and ```Walk/Car```
* Highlight route as panned through, and display information in status bar
* Navigation instructions for car transportation and walk/car transportation, communicated in a clear and easy to understand way

## Images
| Splash Loading Screen  | Map Selection |
| ------------- | ------------- |
| ![Loading Screen](/pictures/SplashScreen.gif)  | ![Map Selection](/pictures/MapSelection.png) |

| Slow Path-finding Algorithm  | Our Improved Path-finding Algorithm |
| ------------- | ------------- |
| ![OptimizedAlgoNOT](/pictures/OptimizedAlgoNOT.gif)  | ![OptimizedAlgo](/pictures/OptimizedAlgo.gif) |

| Status bar Welcome Text  | Zooming In |
| ------------- | ------------- |
| ![Status Bar Welcome](/pictures/StatusBarWelcomeText.png)  | ![Zooming In](/pictures/ZoomingIn.gif) |

| Search Points of Interest  | Show Subways |
| ------------- | ------------- |
| ![Display POI](/pictures/DisplayPOI.png)  | ![Show Subways](/pictures/ShowSubways.png) |

| Auto Complete Search Bar  | Error Messages |
| ------------- | ------------- |
| ![Auto Complete Search](/pictures/AutocompleteSearch.gif)  | ![Error Message](/pictures/ErrorMessage.png) |

| Light Mode  | Dark Mode |
| ------------- | ------------- |
| ![Light Mode](/pictures/LightMode.png)  | ![Dark Mode](/pictures/DarkMode.png) |

| Help Text  | Dark Mode Icons |
| ------------- | ------------- |
| ![Help Text](/pictures/HelpText.png)  | ![Dark Mode With Icons](/pictures/DarkModeWithIcons.png) |

#### Dynamic Street Names
![Dynamic Street Names](/pictures/DynamicStreetNames.gif)  
#### High Detail Mode Toggled
![High Detail Mode](/pictures/HighDetailModeToggle.gif)

| Google Maps  | Our Map |
| ------------- | ------------- |
| ![Google Maps](/pictures/GoogleMapsVSOurMap.png)  | ![Our Map](/pictures/GoogleMapsVSOurMap(2).png) |

#### Navigation Instructions Status Bar
![Navigation Instructions](/pictures/StatusBarNavInfo.png)
#### Selecting Point of Interest as a Start Point
![Selecting Point of Interest as a Start Point](/pictures/SelectingPOIasStartNavigation.gif)
#### Changing Navigation Parameters
![Changing Navigation Parameters](/pictures/ChangingPathFindingParameters.gif)
#### Navigation Route Highlighting Info
![Navigation Route Highlighting Info](/pictures/StatusBarShowHighlightedPathSegmentInstruction.gif)
![Navigation Route Highlighting Info](/pictures/StatusBarShowHighlightedPathSegmentInstruction.png)
#### Navigation Instructions - Car
![Car Navigation Instructions](/pictures/NavigationInstructionsDriving.png)
#### Navigation Instructions - Walk/Car
![Walk/Car Navigation Instructions](/pictures/NavigationInstructionsWalkingAndDriving.png)