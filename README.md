# Featured Projects

I had worked on applications from multiple domains - financial applications and enterprise banking to healthcare, fitness and real-time mobility platforms.

# [Neo Financial](https://apps.apple.com/ca/app/neo-financial/id1495268044)
**Fintech | Digital Banking | 1M+ customers**

I worked as a native iOS engineer within an 8-person mobile team, contributing to Accounts, Promotional Offers, Financial Solutions and Onboarding.

- Delivered native iOS features across Accounts, Promotions and Financial Solutions.
- Led technical analysis for the Financial Solutions feature, breaking requirements into Jira stories and coordinated implementation scenarios with Android and Web engineers.
- Used Cursor and Claude to accelerate feature implementation, delivering the work in 2 sprints against my original 4-sprint estimate without AI assistance.
- Reviewed and refactored AI-generated code into protocol-based services using Swift Concurrency and async/await and verified generated tests.
- Built 5 of 20 Onboarding screens and implemented the native iOS integration for a shared-code React Native migration initiatives and architecture modernization. Reduced Onboarding and Contact Us code from 20,000 lines to 15,000 across platfroms.
- Owned weekly iOS production releases, including release-blocker investigation and resolution.
- Raised Unit Test coverage from 85% to 87% for owned modules and maintained 99.4% crash-free session rate.

**Tech Stack**: Swift, SwiftUI, UIKit, Objective-C, GraphQL, Swift Concurrency, Combine, MVVM, XCTest, XCUITest, CodeMagic, DataDog, Sentry, A/B Testing, VIPER, React Native, TypeScript, AI assisted tools - Claude, Cursor.


# [PNC Mobile Banking](https://apps.apple.com/us/app/pnc-mobile-banking/id303113127)
**Digital Banking | UIKit to SwiftUI Modernization | Banking platform serving ~8 million customers**

My primary focus was migrating legacy UIKit implementations into reusable SwiftUI components and establishing a modular architecture for banking features - Accounts and Transactions.

- Led iOS architecture modernization for the Accounts and Transactions features and migrated approximately 15 legacy UIKit components into reusable SwiftUI frameworks separating Savings, Chequing, HISA, Loan and Credit Card experiences into independent packages.
- Integrated Swift Concurrency and Combine for asynchronous operations and reactive data flows.
- Established reusable components that could be maintained independently.
- Introduced VoiceOver and Dynamic Type support to meet accessibility compliance requirements.
- Onboarded and technically guided 4 iOS engineers through first-sprint delivery, code reviews and bug fixes.
- Reduced peak memory on migrated screens from over 1 GB to about 150 MB, held 85% unit test coverage and a 99.7% crash-free session rate through the migration.

**Tech Stack**: Swift, SwiftUI, UIKit, Combine, Swift Concurrency, XCTest, XCUITest, VoiceOver and Dynamic Type, AppLanga.


# [eCare Vault](https://apps.apple.com/us/app/ecare-vault-mobile-app/id6475713121)
**Healthcare**

eCare Vault is one of the applications I helped build from its early stages into a production healthcare product. The application revolves around patients and their care teams, providing a centralized place to manage patient-related documents, activities and consultations.

- Technically led a cross-platform team of 6 iOS and Android engineers, driving technical decisions, architecture discussions, code reviews and feature delivery.
- Architected patient-centric Care Team and Care Feed experiences, presenting patient activities, updates and care-related notifications.
- Improved Care Feed UX by proposing Figma design enhancements based on user reachability, prioritizing frequently accessed actions within easily reachable screen areas.
- Engineered document signature and document management workflows using Swift Concurrency and TaskGroup, supporting up to 5 parallel downloads with progress tracking, cancellation and background execution.
- Developed JavaScript-enabled patient consultation forms using WebKit, enabling dynamic form rendering and interactive healthcare workflows.
- Integrated SiriKit, App Intents and Spotlight indexing to provide system-level access to Activities, Documents and Forms.
- Established MVVM architecture with DataProvider protocols and migrated the application to Swift 6 strict concurrency, improving maintainability and concurrency safety.
- Improved Care Feed scrolling performance from 16.8 ms to 2.1 ms, contributing to the product's growth from MVP to 5K+ MAU while maintaining 86% test coverage.

**Tech Stack**: Swift, SwiftUI, UIKit, MVVM, Core Data, WebKit, JavaScript, Combine, Swift Concurrency, R.Swift, SiriKit, App Intents, XCTest, Crashlytics, Firebase, AWS.


# [Powermove](https://apps.apple.com/us/developer/rahul-shah/id1506826635)
**Fitness | ARKit | Pose Detection**

Powermove is a fitness application where users follow exercise videos and evaluate their movements against the instructions. One of the interesting engineering challenges was exploring how native Apple technologies could be used to track body movements during exercises.


- Integrated ARKit with Pose Detection to track user movements and explored motion recognition to determine how accurately users followed exercise instructions.
- Architected application handling workout listing, video player integration, Pose Detection and production optimization.
- Reduced peak application memory consumption during multiple workout sessions from over 2 GB to approximately 600 MB through performance profiling.

**Tech Stack**: Swift, UIKit, Realm, ARKit, Pose Detection, Google Cloud Platform, Firebase, Sentry, Intercom, Segment.

# Tram.Global
**Real-Time Location Tracking | Mobility**

Tram.Global combines location tracking, route visualization and mobility analytics to help users understand the environmental impact of their journeys. I worked on the initial application development and later contributed to a revamped application experience with significant UI and performance improvements.


- Architected the application from concept to MVP and Production-ready product by integrating mobility features using Sentiance SDK to analyze transportation behavior, track trips and estimate carbon emissions.
- Implemented route visualization using Mapbox, supporting real-time trip monitoring and rendering mapped route on mobile platforms.
- Modernized the application experience by building reusable SwiftUI and UIKit components, improving consistency across redesigned screens.
- Improved background processing, network efficiency and battery usage to support reliable location tracking without unnecessary resource consumption.
- Profiled application performance using Instruments and optimized trip-list rendering and scrolling, reducing scroll hitch time from 18.4 ms to 3 ms.
- Optimized application startup performance, reducing launch time from 1.6 seconds to 0.7 seconds.
- Automated build, TestFlight distribution and App Store submissions using Fastlane and GitHub Actions, reducing release execution time from 3 hours to 20 minutes.


**Tech Stack**: Swift, UIKit, Realm, Firebase, Sentry, Mapbox, Sentiance SDK, Github Actions, Fastlane.


# LiveSteam
**Real-Time Location Sharing | Mobility**

LiveSteam was an MVP project designed to display the real-time locations of multiple devices on a custom interactive map.


- Architected an MVP application from initial development through TestFlight distribution for internal and external users.
- Integrated WebSockets using Starscream for real-time location updates from multiple devices.
- Researched and decided to use Mapbox for customized map route to layout route for non-standard paths.


**Technology**: Swift, UIKit, Core Data, Firebase, Sentry, Mapbox, Core Location, Starscream, Testflight.

# V-Pass
**Healthcare | Enterprise Communication**

V-Pass is an enterprise healthcare communication application that allows patients to connect with customer care representatives through video calls and I led it from concept through MVP application.

- Architected the MVP by integrating Zoom Video SDK for real-time video communication, Socket.IO for real-time application updates and Wordly SDK to support live translation services to showcase the features for client demo and controlled rollout to specific customers.
- Architected SwiftUI-based application components with asynchronous workflows using Swift Concurrency and Combine.

**Tech Stack**: Swift, SwiftUI, Combine, Swift Concurrency, Zoom Video SDK, Wordly SDK, Socket.IO, Crashlytics.


# IR App & DL App
**Corporate Communications**

- Developed and maintained white-labeled Document Library (DL) and Investor Relations (IR) applications using Objective-C, enabling clients to manage corporate reports, financial documents, company news and share-price information through branded iOS apps.
- Created client-specific production configuration documentation and managed end-to-end release processes, including App Store certification, code signing and distribution of signed or unsigned builds for 100+ branded applications serving London-listed companies such as Vodafone, ArcelorMittal and BP.


# SSH Client
**Developer Tools | Productivity**

- Implemented native Objective-C based terminal application, evolving its functionality based on user feedback and product requirements.
- Improved authentication workflows and implemented RSA key-based authentication to strengthen secure remote access.
- Developed productivity features, including shortcuts and usability enhancements, improving the overall terminal experience.
- Contributed to the product's transition from a freemium to a subscription-based model, helping improve its App Store rating from 3.0 to 4.5 stars.

**Tech Stack**: Objective-C, UIKit.
