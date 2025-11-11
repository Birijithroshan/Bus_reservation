# How to Run the Bus Reservation System

## Quick Start Guide

### Step 1: Navigate to the Source Directory
```cmd
cd C:\Bus_reservation\buss_reservation.java\src
```

### Step 2: Compile the Java Code
```cmd
javac Main.java
```

This will compile `Main.java` and create the necessary `.class` files (Main.class, Bus.class, and Passenger.class).

### Step 3: Run the Application
```cmd
java Main
```

## Sample Usage

Once the program starts, you'll see a menu with these options:

```
==== Bus Reservation System ====
1. View All Buses
2. View Available Seats
3. Book a Seat
4. Cancel a Seat
5. Display All Bookings
6. Exit
```

### Example Workflow:

1. **View All Buses** (Option 1)
   - Shows Bus101 (10 seats) and Bus102 (15 seats)

2. **Book a Seat** (Option 3)
   - Enter Bus ID: `Bus101`
   - Enter Seat Number: `1`
   - Enter Passenger Name: `John Doe`
   - Enter Phone Number: `1234567890`

3. **View Available Seats** (Option 2)
   - Enter Bus ID: `Bus101`
   - Shows remaining available seats

4. **Display All Bookings** (Option 5)
   - Enter Bus ID: `Bus101`
   - Shows all booked seats with passenger details

5. **Cancel a Seat** (Option 4)
   - Enter Bus ID: `Bus101`
   - Enter Seat Number: `1`

6. **Exit** (Option 6)
   - Exits the program

## Requirements

- Java Development Kit (JDK) 8 or higher must be installed
- Make sure `javac` and `java` commands are available in your system PATH

## Troubleshooting

**If you get "javac is not recognized":**
- Install JDK from https://www.oracle.com/java/technologies/downloads/
- Add JDK's bin directory to your system PATH

**If you get compilation errors:**
- Make sure you're in the correct directory: `C:\Bus_reservation\buss_reservation.java\src`
- Ensure Main.java file exists and is not corrupted

## Project Structure
```
Bus_reservation/
└── buss_reservation.java/
    └── src/
        ├── Main.java (contains Main, Bus, and Passenger classes)
        ├── Main.class (generated after compilation)
        ├── Bus.class (generated after compilation)
        └── Passenger.class (generated after compilation)
```

