# WorkspaceHub Project Map

Browser → `/api/spaces` → workspace catalogue

Browser → register/login → JWT → localStorage

Browser → `/api/bookings` → authenticated booking request → conflict validation → booking

Browser → `/api/dashboard` → current user's reservations

Models:
- User: name, email, passwordHash
- Space: name, city, kind, capacity, features, pricePerHour
- Booking: spaceId, userId, date, startTime, endTime, status
