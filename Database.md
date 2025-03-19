//  Stores user details and authentication

{
  "userId": "U12345",
  "name": "John Doe",
  "email": "johndoe@example.com",
  "password": "hashed_password",
  "drivinig licence":"*********",
  "phone": "+91XXXXXXXXXX",
}

// Stores Parking plot details
    
{
  "lotId": "L98765",
  "ownerId": "U12345",
  "name": "XYZ Parking",
  "location": { "lat": 22.5726, "lng": 88.3639 },
  "totalSlots": 20,
  "availableSlots": 5,
  "pricePerHour": 50,
  "facilities": ["CCTV", "EV Charging", "Security Guard"]
}

// Stores bookings details

{
  "bookingId": "B54321",
  "userId": "U12345",
  "lotId": "L98765",
  "carDetails": { "model": "Tesla Model 3", "number": "WB1234" },
  "startTime": "2025-03-11T10:00:00Z",
  "endTime": "2025-03-11T14:00:00Z",
  "amountPaid": 200,
  "status": "Booked/Completed"
}

