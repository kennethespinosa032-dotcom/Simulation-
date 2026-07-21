<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apex Rentals - Professional Vehicle Reservation System</title>
  <style>
    :root {
      --primary: #0f172a;       /* Deep Slate/Navy */
      --accent: #2563eb;        /* Professional Royal Blue */
      --accent-hover: #1d4ed8;
      --bg-body: #f1f5f9;
      --card-bg: #ffffff;
      --text-main: #1e293b;
      --text-muted: #64748b;
      --border: #cbd5e1;
      --radius: 8px;
      --shadow: 0 4px 6px -1px rgba(0,0,0,0.05), 0 2px 4px -2px rgba(0,0,0,0.05);
      --shadow-hover: 0 10px 15px -3px rgba(0,0,0,0.1), 0 4px 6px -4px rgba(0,0,0,0.05);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    body {
      background-color: var(--bg-body);
      color: var(--text-main);
      padding: 24px 16px;
    }

    /* Header Navigation Bar */
    header {
      max-width: 1200px;
      margin: 0 auto 32px auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 16px;
      border-bottom: 2px solid var(--border);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .brand-logo {
      width: 38px;
      height: 38px;
      background: var(--accent);
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: var(--radius);
      font-weight: 800;
      font-size: 1.2rem;
    }

    .brand h1 {
      font-size: 1.5rem;
      color: var(--primary);
      letter-spacing: -0.5px;
    }

    /* Main Container Grid */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr;
      gap: 32px;
    }

    @media (min-width: 960px) {
      .container {
        grid-template-columns: 2.2fr 1fr;
      }
    }

    /* Category Filter Tabs */
    .filter-wrapper {
      margin-bottom: 20px;
      display: flex;
      gap: 8px;
      flex-wrap: wrap;
    }

    .filter-btn {
      background: var(--card-bg);
      border: 1px solid var(--border);
      padding: 8px 18px;
      border-radius: 20px;
      cursor: pointer;
      font-weight: 600;
      font-size: 0.875rem;
      color: var(--text-muted);
      transition: all 0.2s ease;
    }

    .filter-btn.active, .filter-btn:hover {
      background: var(--primary);
      color: #ffffff;
      border-color: var(--primary);
    }

    /* Vehicle Showcase Grid */
    .vehicle-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 20px;
    }

    .vehicle-card {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 20px;
      box-shadow: var(--shadow);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: all 0.2s ease;
    }

    .vehicle-card:hover {
      transform: translateY(-2px);
      box-shadow: var(--shadow-hover);
    }

    .card-top {
      margin-bottom: 16px;
    }

    .badge {
      display: inline-block;
      background: #e0f2fe;
      color: #0369a1;
      font-size: 0.7rem;
      font-weight: 700;
      padding: 3px 8px;
      border-radius: 4px;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 10px;
    }

    .vehicle-card h3 {
      font-size: 1.25rem;
      color: var(--primary);
      margin-bottom: 6px;
    }

    .specs-list {
      display: flex;
      gap: 12px;
      font-size: 0.8rem;
      color: var(--text-muted);
      margin-bottom: 14px;
    }

    .vehicle-price {
      font-size: 1.3rem;
      font-weight: 800;
      color: var(--accent);
    }

    .vehicle-price span {
      font-size: 0.85rem;
      color: var(--text-muted);
      font-weight: 400;
    }

    .select-btn {
      width: 100%;
      background: #ffffff;
      border: 1.5px solid var(--accent);
      color: var(--accent);
      padding: 10px;
      border-radius: var(--radius);
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s ease;
    }

    .select-btn:hover, .select-btn.selected {
      background: var(--accent);
      color: #ffffff;
    }

    /* Booking Form Panel */
    .booking-panel {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 24px;
      box-shadow: var(--shadow);
      height: fit-content;
      position: sticky;
      top: 24px;
    }

    .booking-panel h2 {
      font-size: 1.25rem;
      color: var(--primary);
      margin-bottom: 18px;
      padding-bottom: 12px;
      border-bottom: 1px solid var(--border);
    }

    .form-group {
      margin-bottom: 16px;
    }

    .form-group label {
      display: block;
      font-size: 0.85rem;
      font-weight: 600;
      color: var(--primary);
      margin-bottom: 6px;
    }

    .form-group input, .form-group select {
      width: 100%;
      padding: 10px 12px;
      border: 1px solid var(--border);
      border-radius: var(--radius);
      font-size: 0.9rem;
      color: var(--text-main);
      background-color: #fff;
    }

    .form-group input:focus, .form-group select:focus {
      outline: none;
      border-color: var(--accent);
      box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
    }

    /* Financial Calculation Box */
    .summary-box {
      background: #f8fafc;
      border: 1px solid var(--border);
      padding: 16px;
      border-radius: var(--radius);
      margin: 20px 0;
    }

    .summary-row {
      display: flex;
      justify-content: space-between;
      margin-bottom: 8px;
      font-size: 0.875rem;
      color: var(--text-muted);
    }

    .summary-row.total {
      font-weight: 700;
      font-size: 1.1rem;
      border-top: 1px solid var(--border);
      padding-top: 10px;
      margin-top: 10px;
      margin-bottom: 0;
      color: var(--primary);
    }

    .summary-row.total span:last-child {
      color: var(--accent);
    }

    .submit-btn {
      width: 100%;
      background: var(--accent);
      color: #ffffff;
      border: none;
      padding: 12px;
      border-radius: var(--radius);
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: background 0.2s ease;
    }

    .submit-btn:hover {
      background: var(--accent-hover);
    }

    /* Notification Alert */
    .alert {
      padding: 14px;
      border-radius: var(--radius);
      font-size: 0.875rem;
      margin-top: 16px;
      display: none;
      line-height: 1.4;
    }

    .alert.success {
      background: #f0fdf4;
      color: #166534;
      border: 1px solid #bbf7d0;
    }
  </style>
</head>
<body>

  <header>
    <div class="brand">
      <div class="brand-logo">A</div>
      <h1>Apex Drive PH</h1>
    </div>
    <span style="font-size: 0.875rem; color: var(--text-muted);">Vehicle Fleet Management</span>
  </header>

  <div class="container">
    <!-- Left Panel: Fleet Listing -->
    <main>
      <div class="filter-wrapper">
        <button class="filter-btn active" onclick="filterCategory('All')">All Fleet</button>
        <button class="filter-btn" onclick="filterCategory('Sedan')">Sedans</button>
        <button class="filter-btn" onclick="filterCategory('SUV')">SUVs / MPVs</button>
        <button class="filter-btn" onclick="filterCategory('Motorcycle')">Motorcycles</button>
      </div>

      <div class="vehicle-grid" id="vehicleContainer"></div>
    </main>

    <!-- Right Panel: Reservation Form -->
    <aside class="booking-panel">
      <h2>Reserve a Vehicle</h2>
      <form id="bookingForm" onsubmit="handleBooking(event)">
        
        <div class="form-group">
          <label for="selectedVehicle">Vehicle Selection</label>
          <select id="selectedVehicle" onchange="onSelectDropdownChange()" required>
            <option value="" disabled selected>Select a vehicle...</option>
          </select>
        </div>

        <div class="form-group">
          <label for="customerName">Full Name</label>
          <input type="text" id="customerName" placeholder="e.g., Juan Dela Cruz" required>
        </div>

        <div class="form-group">
          <label for="pickupDate">Pickup Date</label>
          <input type="date" id="pickupDate" onchange="calculateTotal()" required>
        </div>

        <div class="form-group">
          <label for="returnDate">Return Date</label>
          <input type="date" id="returnDate" onchange="calculateTotal()" required>
        </div>

        <!-- Summary Calculation Box -->
        <div class="summary-box">
          <div class="summary-row">
            <span>Rental Duration:</span>
            <span id="rentalDays">0 days</span>
          </div>
          <div class="summary-row">
            <span>Daily Rate:</span>
            <span id="dailyRate">₱0.00</span>
          </div>
          <div class="summary-row total">
            <span>Total Estimated Cost:</span>
            <span id="totalPrice">₱0.00</span>
          </div>
        </div>

        <button type="submit" class="submit-btn">Confirm Booking</button>
      </form>

      <div id="statusAlert" class="alert success"></div>
    </aside>
  </div>

  <script>
    // --- Data Model in PHP (Philippine Peso) ---
    const vehicles = [
      { id: 1, name: "Toyota Vios", category: "Sedan", pricePerDay: 1800, transmission: "Auto", seats: "5 Seats" },
      { id: 2, name: "Honda City", category: "Sedan", pricePerDay: 2000, transmission: "Auto", seats: "5 Seats" },
      { id: 3, name: "Toyota Innova", category: "SUV", pricePerDay: 3200, transmission: "Manual", seats: "7 Seats" },
      { id: 4, name: "Mitsubishi Montero", category: "SUV", pricePerDay: 4500, transmission: "Auto", seats: "7 Seats" },
      { id: 5, name: "Yamaha NMAX 155", category: "Motorcycle", pricePerDay: 800, transmission: "Auto", seats: "2 Seats" },
      { id: 6, name: "Honda Click 125i", category: "Motorcycle", pricePerDay: 600, transmission: "Auto", seats: "2 Seats" }
    ];

    let currentSelectedId = null;

    // --- DOM Elements ---
    const vehicleContainer = document.getElementById("vehicleContainer");
    const dropdown = document.getElementById("selectedVehicle");
    const pickupInput = document.getElementById("pickupDate");
    const returnInput = document.getElementById("returnDate");

    // Format utility for PHP Currency
    const formatPHP = (amount) => {
      return new Intl.NumberFormat('en-PH', {
        style: 'currency',
        currency: 'PHP'
      }).format(amount);
    };

    // Set today as minimum pickup date
    const today = new Date().toISOString().split("T")[0];
    pickupInput.min = today;
    returnInput.min = today;

    // --- Render Fleet Items ---
    function renderVehicles(categoryFilter = "All") {
      vehicleContainer.innerHTML = "";
      
      const filtered = categoryFilter === "All" 
        ? vehicles 
        : vehicles.filter(v => v.category === categoryFilter);

      filtered.forEach(vehicle => {
        const isSelected = vehicle.id === currentSelectedId;
        const card = document.createElement("div");
        card.className = "vehicle-card";
        card.innerHTML = `
          <div class="card-top">
            <span class="badge">${vehicle.category}</span>
            <h3>${vehicle.name}</h3>
            <div class="specs-list">
              <span>⚙️ ${vehicle.transmission}</span>
              <span>👥 ${vehicle.seats}</span>
            </div>
            <div class="vehicle-price">${formatPHP(vehicle.pricePerDay)} <span>/ day</span></div>
          </div>
          <button 
            type="button" 
            class="select-btn ${isSelected ? 'selected' : ''}" 
            onclick="selectVehicle(${vehicle.id})">
            ${isSelected ? 'Selected' : 'Select Vehicle'}
          </button>
        `;
        vehicleContainer.appendChild(card);
      });
    }

    function populateDropdown() {
      dropdown.innerHTML = '<option value="" disabled selected>Select a vehicle...</option>';
      vehicles.forEach(vehicle => {
        const option = document.createElement("option");
        option.value = vehicle.id;
        option.textContent = `${vehicle.name} (${formatPHP(vehicle.pricePerDay)}/day)`;
        dropdown.appendChild(option);
      });
    }

    // --- Business Logic ---
    function filterCategory(category) {
      document.querySelectorAll(".filter-btn").forEach(btn => {
        btn.classList.toggle("active", btn.textContent.includes(category) || (category === 'All' && btn.textContent === 'All Fleet'));
      });
      renderVehicles(category);
    }

    function selectVehicle(id) {
      currentSelectedId = id;
      dropdown.value = id;
      
      const activeBtn = document.querySelector(".filter-btn.active");
      const currentCategory = activeBtn.textContent.replace(' Fleet', '').replace('s', '').trim();
      
      renderVehicles(currentCategory === 'All' ? 'All' : currentCategory);
      calculateTotal();
    }

    function onSelectDropdownChange() {
      const selectedId = parseInt(dropdown.value);
      selectVehicle(selectedId);
    }

    function calculateTotal() {
      const vehicle = vehicles.find(v => v.id === currentSelectedId);
      const pickupDate = new Date(pickupInput.value);
      const returnDate = new Date(returnInput.value);

      if (!vehicle || isNaN(pickupDate) || isNaN(returnDate)) {
        updateSummary(0, vehicle ? vehicle.pricePerDay : 0, 0);
        return;
      }

      if (returnDate <= pickupDate) {
        returnInput.setCustomValidity("Return date must be later than the pickup date.");
        updateSummary(0, vehicle.pricePerDay, 0);
        return;
      } else {
        returnInput.setCustomValidity("");
      }

      const timeDiff = returnDate.getTime() - pickupDate.getTime();
      const days = Math.ceil(timeDiff / (1000 * 3600 * 24));
      const total = days * vehicle.pricePerDay;

      updateSummary(days, vehicle.pricePerDay, total);
    }

    function updateSummary(days, rate, total) {
      document.getElementById("rentalDays").textContent = `${days} day${days !== 1 ? 's' : ''}`;
      document.getElementById("dailyRate").textContent = formatPHP(rate);
      document.getElementById("totalPrice").textContent = formatPHP(total);
    }

    function handleBooking(event) {
      event.preventDefault();

      const customerName = document.getElementById("customerName").value;
      const vehicle = vehicles.find(v => v.id === currentSelectedId);
      const daysText = document.getElementById("rentalDays").textContent;
      const totalText = document.getElementById("totalPrice").textContent;

      if (!vehicle) {
        alert("Please select a vehicle to proceed.");
        return;
      }

      const alertBox = document.getElementById("statusAlert");
      alertBox.style.display = "block";
      alertBox.innerHTML = `<strong>Booking Confirmed!</strong><br>Thank you, ${customerName}. You reserved the <strong>${vehicle.name}</strong> for ${daysText}. Total: <strong>${totalText}</strong>.`;

      // Reset form
      document.getElementById("bookingForm").reset();
      currentSelectedId = null;
      renderVehicles("All");
      updateSummary(0, 0, 0);

      setTimeout(() => {
        alertBox.style.display = "none";
      }, 6000);
    }

    // Initial load
    renderVehicles();
    populateDropdown();
  </script>
</body>
</html>
