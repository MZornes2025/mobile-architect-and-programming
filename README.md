# Inventory App - Project Two

## 📱 App Overview
The **Inventory App** is an Android application designed to help warehouse employees efficiently track and manage inventory items. The app provides a secure login system, intuitive inventory grid layout, comprehensive item management capabilities, and SMS notifications for low stock alerts.

### Primary Goals
- Secure user authentication and account management
- Real-time inventory visibility with visual indicators
- Streamlined item management (add/remove/update quantities)
- Automated low stock notifications via SMS
- Mobile-optimized interface for warehouse environments

### User Needs Addressed
- Reduced manual tracking errors and paperwork
- Immediate visibility into stock levels across warehouse
- Timely alerts for restocking needs
- Mobile accessibility for on-the-go inventory management
- Simple, intuitive interface requiring minimal training

## 🎨 User-Centered Design

### Screens & Features
| Screen | Key Features | User Benefit |
|--------|-------------|-------------|
| **Login** | Secure auth, password obscuring, dual login/registration | Quick access, account security |
| **Dashboard** | Grid layout, color-coded quantities, action buttons | At-a-glance inventory status |
| **SMS Permissions** | Contextual explanation, graceful denial handling | Informed permission decisions |

### Design Philosophy
The UI was designed specifically for warehouse workers:
- **Large touch targets** for glove compatibility
- **Color-coded visual indicators** for quick status assessment
- **Streamlined navigation** minimizing required taps
- **Consistent Material Design** themes for intuitive interaction
- **Logical focus order** matching natural workflow patterns

## 💻 Development Approach

### Implementation Strategy
- **Incremental development** with core navigation first
- **UI before logic** methodology for early visual validation
- **Modular component design** for reusability
- **Progressive enhancement** with thorough testing at each stage

### Technical Architecture
```plaintext
App Structure:
- MainActivity (Login/Registration)
- DashboardActivity (Inventory Management) 
- SmsPermissionActivity (Notifications)
- RecyclerView with Custom Adapter
- SQLite Database for local storage
