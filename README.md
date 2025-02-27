![Distillery](https://distillery.com/content/uploads/2018/07/logo.svg)

# Distillery growing course

- [Distillery growing course](#distillery-growing-course)
- [Frontend (General)](#frontend-general)
  - [Prerequisites](#prerequisites)
  - [Network (Basic)](#network-basic)
  - [Semantic HTML (Basic)](#semantic-html-basic)
  - [CSS (Basic)](#css-basic)
  - [HTML / CSS tools (Basic)](#html--css-tools-basic)
  - [CSS pre- & post- processors](#css-pre---post--processors)
  - [CSS Architecture](#css-architecture)
  - [Package managers](#package-managers)
  - [CSS Frameworks](#css-frameworks)
  - [Build tools](#build-tools)
  - [JavaScript (ES2018)](#javascript-es2018)
  - [JS Networking](#js-networking)
  - [TypeScript](#typescript)
  - [RxJS](#rxjs)
- [Frontend - Angular](#frontend---angular)
  - [Angular](#angular)
- [Frontend - React](#frontend---react)
- [Frontend - Vue](#frontend---vue)
- [Mobile - React Native](#mobile---react-native)
  - [React-Native cross-platform [Basic]](#react-native-cross-platform-basic)
  - [React-Native [Intermediate]](#react-native-intermediate)
  - [React-Native [Advanced]](#react-native-advanced)

# Frontend (General)

## Prerequisites

Basic development principles, general for any development path

- Data structures and algorithms
- Design patterns
- SOLID, KISS, YAGNI
- Licenses
- Semantic versioning
- Character encodings

## Network (Basic)

How modern networks work from developers POV

- IP
- TCP
- UDP
- HTTP
- HTTP/2
- QUIC
- TLS, SSL
- DNS
- NTP

## Semantic HTML (Basic)

Basic HTML/Web

- What is "semantics" and why do we need it?
- Document structure
- Head and metadata
- Hyperlinks. A fundament of the Web.
- Block and inline elements
- Headers
- Paragraphs
- Text: emphasis and importance
- Whitespaces in HTML
- Special characters
- Lists
- Nested lists
- Tables
- Multimedia and embedding
- Images
- Video and audio content
- Vector graphics
- Responsive images
- Objects and IFrames
- Forms
  - Label
  - Input (+types)
  - Select
  - Textarea
  - Validation
  - Button

## CSS (Basic)

- Basic syntax
- Selectors
  - Element selectors
  - Class selectors
  - ID selectors
  - Universal selector \*
  - Attribute selectors
  - Combinators and selector list
  - Selector specificity
- Pseudo classes and pseudo-elements
- Layout
  - Floats
  - Positioning
  - Display
  - Box model
  - CSS Grid
  - Flexbox
- CSS values and units
- Cascade and inheritance
- Fonts
- Styling font and text layout
- Styling lists
- Styling links

## HTML / CSS tools (Basic)

- Chrome inspector
- Firefox inspector
- Safari inspector
- HTML validation
- CSS validation

## CSS pre- & post- processors

- SCSS
  - Import - fragments, nested imports, index
  - Mixins, @extend
  - SassScript
- PostCSS
  - Autoprefixer
  - CSSNext
  - PreCSS
  - Stylelint

## CSS Architecture

- Isolation
- Specificity wars
- Garbage collection
- BEM

## Package managers

- Licenses (ref to **Prerequisites**)
- Semantic versioning (ref to **Prerequisites**)
- NPM
  - Dependencies, dev-devependencies
  - Package scope, access level, visibility
  - Publishing
  - Scripts
  - Audit & Security
- Yarn

## CSS Frameworks

- Bootstrap
- Materialize CSS
- Bulma
- Semantic UI

## Build tools

- Task runners
  - NPM scripts
  - Gulp
- Bundlers
  - Webpack
  - Parcel
  - Rollup
- Linters & formaters
  - Prettier
  - ESLint
  - Stylelint
  - TSLint (will be deprecvtaed soon)

## JavaScript (ES2018)

- Grammar and types
- Control flow & error handling
- Loops & iteration
- Functions
  - Arrow functions
- Closures
- Expressions & operators
- Numbers & dates
- Text formatting
- Resular expressions
- Arrays (indexed collections)
- Map, WeakMap, Set (keyed collections)
- Objects, prototypical inheritance
- Promises
  - Async/await syntax
- Iterators & generators
- Meta-programming
  - Handlers & traps
  - Proxy
  - Revocable proxy
  - Reflection
- Strict mode
- Template literals
- Symbols
- Spread operator, rest parameters
- Shared memory, ArrayBuffer, TypedObject
- Eventloop

## JS Networking

- XHR
  - CORS
- WebSockets

## TypeScript

- Basic types
- Variable declarations
- Interfaces
- Classes
- Functions
- Generics
- Enums
- Type inference
- Type compatibility
- Advanced types
  - Intersection of types
  - Union types
  - Type guards
  - String literal types
  - Index types
  - Mapped types
  - Conditional types
    - Exclude<T, U>
    - Extract<T, U>
    - NonNullable<T>
    - ReturnType<T>
    - InstanceType<T>
- Symbols
- Iterators & generators
- Modules
  - Module resolution
- Namespaces
- Declaration merging
- JSX / TSX
- Decorators
- Mixins
- Publishing

## RxJS

- Observables
  - Hot
  - Cold
- Operators
  - Combination
  - Conditional
  - Creation
  - Error handling
  - Multicasting
  - Filtering
  - Transformation
  - Utility
- Subjects
  - AsyncSubject
  - BehaviorSubject
  - ReplaySubject
  - Subject

![Angular](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/250px-Angular_full_color_logo.svg.png)

# Frontend - Angular

## Angular

- CLI - Command line interface
- Schematics
- Modules
  - JS modules vs Angular modules
  - Feature modules
    - Domain feature modules
    - Routed feature modules
    - Routing modules
    - Service feature modules
    - Widget feature modules
  - Entry components
  - Declarations
  - Providers
  - Lazy loading feature modules
  - Sharing modules
- Components
- Services and DI
  - Hierarchical dependency injectors
  - DI providers
  - Singleton services
- Templates
  - Template syntax
  - Lifecycle hooks
  - User input
  - Component interaction
  - Component styles
  - Angular components (Custom elements)
  - Dynamic components
    - Factories
    - Outlets
- Attribute directives
- Structural directives
- Pipes
- Forms
  - Reactive forms
  - Dynamic forms
  - Template-driven forms
  - Validation
- Observables in Angular
- HTTPClient
- Routing & Navigation
- Animations
- Bootstraping
- Internalization
- Angular libraries
- Server-side rendering
- Service workers & PWA
- Security
  - XSS
  - CSRF
  - XSSI
- AOT (Ahead of time) compilation
- Testing

![React](https://miro.medium.com/max/480/1*To2H39eauxaeYxYMtV1afQ.png)

# Frontend - React

# Frontend - Vue

# Mobile - React Native

## React-Native cross-platform [Basic]

- Project scaffolding
  - CRNA (create-react-native-app)
  - Expo SDK
  - Adding TypeScript to CRNA app
- Basic React usage (see [Frontend - React](#frontend---react))
- React Context API
- Styles & Stylesheet
- Flexbox layout
- Networking
  - XHR
  - Fetch API
  - WebSocket support
- Storages
  - AsyncStorage
- Components
  - Text
  - Text input
  - Button
  - Touchables
  - Gesture responder
  - ScrollView
  - List views
    - Flat list
    - Section list
    - Virtualized list
    - Swipeable list view
  - Image
    - Static resources
    - Network resources
    - URI Data images
    - Cache control (iOs)
    - Background image (via Nesting)
  - Picker
  - Slider
  - Switch
  - ActivityIndicator
  - Alert
  - Animated
  - CameraRoll
  - Clipboard
  - Dimensions
  - KeyboardAvoidingView
  - Linking
  - Modal
  - PixelRatio
  - RefreshControl
  - StatusBar
  - WebView
- Animations
- Accessibility
- Navigation
- Timers
- Running
  - on iOS simulator
  - on iOS device
  - on Android simulator
  - on Android device
- Debugging
- Performance profiling
- App publishing

## React-Native [Intermediate]

- iOs-specific components
  - ActionSheetIOS
  - AlertIOS
  - DatePickerIOS
  - ImagePickerIOS
  - NavigatorIOS
  - ProgressViewIOS
  - PushNotificationIOS
  - SegmentedContolIOS
  - TabBarIOS
- Android-specific components
  - BackHandler
  - DatePickerAndroid
  - DrawerLayoutAndroid
  - PermissionsAndroid
  - ProgressBarAndroid
  - TimePickerAndroid
  - ToastAndroid
  - ToolbarAndroid
  - ViewPagerAndroid
- Expo SDK (most used components)
  - AppAuth
  - AppLoading
  - Asset
  - Audio
  - AuthSession
  - AV
  - BackgroundFetch
  - Calendar
  - Camera
  - Contacts
  - DocumentPicker
  - FileSystem
  - Font
  - GestureHandler
  - ImagePicker
  - IntentLauncherAndroid
  - KeepAwake
  - LinearGradient
  - Linking
  - Location
  - MapView
  - MediaLibrary
  - Notifications
  - Payments
  - Permissions
  - SecureStore
  - Sensors
  - SMS
  - SplashScreen
  - Svg
  - TaskManager
  - Updates
  - Video
  - WebBrowser

## React-Native [Advanced]

- Integration with Existing Apps
- Creating native modules
  - iOS
  - Android
- Communication between native and React Native
- Using Jest for JS test
- Using Detox for iOs
- Using Appium
- Working with stack trace
