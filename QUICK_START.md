# SIBUU HOTEL RESERVATION PLATFORM - Quick Start Guide

## 🚀 Getting Started in 5 Minutes

### Step 1: Open the Application

1. Navigate to the project folder
2. Double-click `index.html` or right-click and open with your browser
3. Alternatively, use a local server:
   ```bash
   # If you have Python installed
   python -m http.server 8000
   
   # If you have Node.js installed
   npx http-server
   ```

### Step 2: Login

Use one of these default accounts:

**Administrator Account:**
- Username: `admin`
- Password: `admin123`
- Role: `Administrator`

**Receptionist Account:**
- Username: `receptionist`
- Password: `recept123`
- Role: `Receptionist`

### Step 3: Explore the Dashboard

After logging in, you'll see:
- Statistics cards showing total rooms, guests, reservations
- Recent reservations table
- Navigation sidebar with all modules

### Step 4: Add Your First Room

1. Click **"Rooms"** in the sidebar
2. Click **"Add Room"** button
3. Fill in the details:
   - Room Number: 101
   - Room Type: Single
   - Price Per Night: 1500
   - Capacity: 2
   - Status: Available
4. Click **"Save Room"**

### Step 5: Register a Guest

1. Click **"Guests"** in the sidebar
2. Click **"Register Guest"** button
3. Fill in guest details:
   - Full Name: John Doe
   - Phone: +251911234567
   - Email: john@email.com
   - ID Number: ID123456
4. Click **"Save Guest"**

### Step 6: Create a Reservation

1. Click **"Reservations"** in the sidebar
2. Click **"New Reservation"** button
3. Select the guest and room you created
4. Choose check-in and check-out dates
5. Enter number of guests
6. System automatically calculates total cost
7. Click **"Save Reservation"**

### Step 7: Record a Payment

1. Click **"Payments"** in the sidebar
2. Click **"Record Payment"** button
3. Select the reservation
4. View the outstanding balance
5. Enter payment amount and method
6. Click **"Save Payment"**
7. View or print the receipt

### Step 8: Generate Reports

1. Click **"Reports"** in the sidebar
2. Select date range
3. Click **"Generate Report"**
4. View occupancy, revenue, and guest statistics
5. Click **"Export"** to download report data

## 📱 Key Features to Try

### Search and Filter
- Use search boxes to find records quickly
- Use dropdown filters to filter by status or type

### Edit and Delete
- Click the pencil icon to edit any record
- Click the trash icon to delete (with confirmation)

### View History
- In guests page, click history icon to view guest's reservation history
- In payments page, click receipt icon to view payment receipt

### Mobile Responsive
- Resize your browser to see responsive design
- Click the menu icon on mobile to toggle sidebar

## 🔧 Data Management

### Local Storage
- All data is stored in your browser's local storage
- Data persists across browser sessions
- To reset data: Clear browser data for this site

### Sample Data
- The `data/sample-data.json` file contains example data
- You can reference this for data structure

### Backup Your Data
- Use browser developer tools to export localStorage
- Or add export functionality to save important data

## ⚠️ Important Notes

1. **Browser Compatibility**: Works best on Chrome, Firefox, Edge
2. **Data Privacy**: Data is stored locally, not shared between browsers
3. **Security**: This is a demo - passwords are not encrypted
4. **Production Use**: Requires backend integration for real deployment

## 🎯 Common Tasks

### Change Room Status
1. Go to Rooms page
2. Click edit icon on any room
3. Change status (Available, Occupied, Maintenance, Cleaning)
4. Save changes

### Cancel a Reservation
1. Go to Reservations page
2. Click the X icon on the reservation
3. Confirm cancellation
4. Status changes to "Cancelled"

### Update Reservation Status
1. Go to Reservations page
2. Click edit icon
3. Change status:
   - Pending → Confirmed → Checked-in → Completed
4. Save changes

### View Payment History
1. Go to Payments page
2. All payments are listed with reservation details
3. Click receipt icon to view full receipt

## 🔐 User Management (Admin Only)

If logged in as Administrator:
1. Click **"Users"** in sidebar
2. Add, edit, or deactivate user accounts
3. Assign roles (Administrator or Receptionist)

## 💡 Tips & Tricks

1. **Quick Navigation**: Use sidebar to switch between modules
2. **Search**: Type in search boxes to filter tables instantly
3. **Date Validation**: System prevents booking conflicts automatically
4. **Cost Calculation**: Total cost calculates automatically based on nights
5. **Outstanding Balance**: System tracks partial payments automatically

## 🐛 Troubleshooting

**Problem**: Can't login  
**Solution**: Check username, password, and role are all selected correctly

**Problem**: Reservation won't save  
**Solution**: Check date range - checkout must be after checkin

**Problem**: Can't delete room  
**Solution**: Rooms with active reservations cannot be deleted

**Problem**: Payment amount too high  
**Solution**: Payment cannot exceed outstanding balance

## 📚 Next Steps

1. ✅ Complete the quick start tutorial above
2. 📖 Read the full README.md for detailed documentation
3. 🧪 Test all features with sample data
4. 🎨 Customize colors and branding if needed
5. 🔧 Consider backend integration for production

## 🆘 Need Help?

- Check the README.md for full documentation
- Review the project guideline document
- Check browser console for error messages
- Verify all files are in correct folders

---

**Congratulations!** You're now ready to use the SIBUU Hotel Reservation Platform.

*Built with ❤️ for efficient hotel management*
