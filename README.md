 Kids-Carpooling-System
A system for managing kids' carpooling between parents and verified drivers. Enables ride scheduling, driver booking, and rating management.
Key Features:

>Parent-driver matching with availability tracking.

>Secure ride booking system.

>Post-ride rating and feedback.

>Real-time ride offer processing.

Components Explanation:

>Parent: Creates ride offers and manages children's profiles.

>Driver: Books rides and sets availability schedules.

>CarpoolSystem: Core coordinator with three subsystems.

>Authentication: Verifies user types (Parent/Driver).

>Ride Matching: Processes offers against driver availability.

>Booking Management: Handles ride reservations and ratings.

Interesting Technical Challenges That We Might Face

> Multiple drivers trying to book the same ride simultaneously.

>  Matching multiple of offers with drivers efficiently.

>  Some drivers receive too many offers, others too few.

> Expired offers consuming memory.
