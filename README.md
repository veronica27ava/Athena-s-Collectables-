# AthenasCollectables-
A website where people can post their products and advertise it for free where the sellers goal to provide a fair price to all while still earning 



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Findscape - Trading Card Marketplace</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo-section">
                <img id="siteLogo" src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%234f46e5'/%3E%3Ctext x='50' y='50' text-anchor='middle' dy='.3em' fill='white' font-size='40' font-weight='bold'%3EFS%3C/text%3E%3C/svg%3E" alt="Findscape Logo" class="navbar-logo">
                <span class="site-name">FINDSCAPE</span>
            </div>
            <div class="nav-menu">
                <a href="#" onclick="navigateTo('home')">Home</a>
                <a href="#" onclick="navigateTo('marketplace')">Marketplace</a>
                <a href="#" onclick="navigateTo('analytics')">Analytics</a>
                <div class="user-menu">
                    <button id="userBtn" class="user-btn" onclick="toggleUserMenu()">
                        <i class="fas fa-user-circle"></i> <span id="userDisplay">Guest</span>
                    </button>
                    <div id="userDropdown" class="user-dropdown">
                        <a href="#" onclick="navigateTo('profile')"><i class="fas fa-user"></i> My Profile</a>
                        <a href="#" onclick="navigateTo('my-listings')"><i class="fas fa-th"></i> My Listings</a>
                        <a href="#" onclick="navigateTo('seller-dashboard')"><i class="fas fa-chart-line"></i> Seller Dashboard</a>
                        <a href="#" onclick="navigateTo('messages')"><i class="fas fa-envelope"></i> Messages</a>
                        <a href="#" onclick="navigateTo('admin-dashboard')" id="adminLink" style="display:none;"><i class="fas fa-cog"></i> Admin Panel</a>
                        <hr>
                        <a href="#" onclick="logout()"><i class="fas fa-sign-out-alt"></i> Logout</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>
    




