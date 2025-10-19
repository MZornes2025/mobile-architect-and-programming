# Inventory App - Project Two

# Mariana's ePortfolio
*Computer Science Portfolio | Android Developer*

---

## Professional Self-Assessment

This ePortfolio represents my journey through the Computer Science program, showcasing my growth into a professional software developer. Through enhancing an Inventory Management Android application, I demonstrate technical proficiency, analytical thinking, and security-minded development.

### Skills Demonstrated:
- **Software Design & Engineering:** Refactored codebase, eliminated duplication, implemented professional coding standards
- **Algorithms & Data Structure:** Optimized performance with DiffUtil, implemented robust input validation
- **Databases:** Secured user data with BCrypt password hashing, implemented database migrations
- **Collaboration & Communication:** Partnered on code review, authored technical narratives

### Course Outcomes Achieved:
- ✅ Employ strategies for building collaborative environments
- ✅ Design and deliver professional-quality communications
- ✅ Design computing solutions using algorithmic principles
- ✅ Use innovative techniques and tools in computing practices
- ✅ Develop a security mindset to ensure data privacy and security

---

## Code Review
[Link to your code review video here]

*Analysis of original code and enhancement planning across three categories*

---

## Enhanced Artifacts

### 1. Software Design & Engineering
**Enhancements:** Code refactoring, BaseRepository pattern, Constants implementation
- [View Enhanced Code](./)

### 2. Algorithms & Data Structure  
**Enhancements:** DiffUtil implementation, input validation, performance optimization
- [View Enhanced Code](./)

### 3. Databases
**Enhancements:** BCrypt password hashing, secure authentication, database migrations
- [View Enhanced Code](./)

---

## Contact
[Your email or LinkedIn profile]

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
