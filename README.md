# Budget Wise - Financial Planning App (React Native)

**Budget Wise** is a mobile financial planning application designed to help users manage their personal finances more intelligently and easily. Take control of your income and expenses, create effective budgets, and achieve your financial goals.

This project serves as a **portfolio** example.
The primary objective of this application is to apply comprehensive mobile app development concepts—from initial design to the implementation of functionality—using React Native and Supabase.

## Key Features
-   💸 **Comprehensive Transaction Management**: Record, edit, delete, and filter income/expenses using customizable categories.
-   📊 **Smart Budgeting & Alerts**: Set budgets by category, monitor progress visually (🟢🟡🔴), and receive automatic notifications when approaching or exceeding your limits.
-   🎯 **Savings Challenge System**: Participate in existing savings challenges or create your own custom challenges to stay motivated in reaching your financial goals.
-   📈 **Data Analysis & Visualization**: Gain insights into your financial habits through interactive dashboards, trend charts, and expense maps.
-   🔐 **Multi-layered Security**: Secure login via email/password, support for biometric authentication, and a "privacy mode" to hide your account balances.
-   ☁️ **Backup & Notifications**: Automatic or manual backup systems, plus smart notifications for daily reminders, budget updates, and progress on your savings challenges.

## Technologies Used
* **Framework**: **React Native**
* **Language**: **JavaScript / TypeScript**
* **Backend & Database**: **Supabase**
* **PostgreSQL Database**: For storing all transaction, budget, and user data. 
* **Supabase Auth**: For managing user authentication, including email/password login. 
* **Realtime APIs**: For real-time data synchronization across devices.
* **Key Supporting Libraries**:
* **React Navigation**: For navigation management and transitioning between screens. 
* **React Native Maps**: For displaying the expense location map feature (*Expense Map*). 
* **React Native Chart Kit**: For creating graphs and charts to visualize financial data. 
* **React Native Biometrics**: For implementing biometric login (fingerprint or facial recognition).

### Navigasi Utama
* 🏠 **Dashboard**: Menampilkan ringkasan saldo, transaksi terbaru, dan status budget.
* 💰 **Transaksi**: Halaman untuk melihat seluruh riwayat transaksi. Dilengkapi fitur filter dan pencarian.
* 📊 **Budget**: Mengelola semua anggaran yang telah Anda buat dan memonitor progresnya.
* 🎯 **Tantangan**: Berisi daftar tantangan menabung yang bisa diikuti atau dibuat sendiri.
* ⚙️ **Lainnya**: Akses ke menu Pengaturan, Profil Pengguna, Keamanan, dan fitur lainnya.

### Managing Transactions
* **Add Transaction**: Tap the **"+"** icon in the navigation menu, select the type (Income/Expense), then enter details such as the amount, category, and description. Tap **"Save"**.
* **Edit & Delete**: In the transaction list, tap an item to view its details. Use the *edit* icon to make changes or the *delete* icon to remove it.
* **Filter Transactions**: Use the options at the top of the Transactions page to filter by date or category, or search by description.

### Budget Management
* **Create a Budget**: Go to the **Budget** tab, tap **"Add Budget"**, then enter the name, category, amount, and period (e.g., Monthly).
* **Monitor Progress**: Each budget displays a progress bar with color-coded status indicators:
* 🟢 **On Track**: Spending is within safe limits. 
* 🟡 **Warning**: Spending has reached 80% of the limit. 
* 🔴 **Over Budget**: Spending has exceeded the limit.
* **Automatic Alerts**: The app will send notifications when a budget reaches 80% of its limit and when it has been exceeded.

### Challenge System
* **Select a Challenge**: Browse the list of available challenges in the **Challenges** tab, choose one you like, and tap **"Join Challenge"**.
* **Create Your Own Challenge**: Use the **"Create Challenge"** option, then specify a name, target amount, and duration.
* **Update Progress**: For each active challenge, you can manually update your progress toward the goal.

### Financial Analysis
* **Dashboard Reports**: Quickly check your total balance, a summary of income/expenses for the current month, and your budget utilization.
* **Visual Charts**: View trends in income versus expenses, a breakdown of spending by category, and budget performance through charts. * **Expense Map**: A feature that provides a visual representation of the geographical locations where you have made expenditures (if location data is enabled).

## Additional Information
### Security Features
* **Biometric Login**: Enable this via the **Settings > Security** menu for faster and more secure access.
* **Privacy Mode**: Hide your account balance and transaction details on the dashboard with a single tap—perfect for maintaining your privacy when in public.
* **Auto Logout**: Set an automatic logout duration (1–30 minutes) for extra security whenever the app is left idle.

### Backup & Restore
* **Auto Backup**: Schedule automatic data backups to the cloud (daily, weekly, or monthly).
* **Manual Backup**: Perform a backup at any time via **Settings > Backup & Restore > "Back Up Now"**.
* **Restore Data**: Recover your data from saved backup history or by manually uploading a backup file.

### Notifications
* Customize the types of notifications you wish to receive via **Settings > Notifications**.
* Get budget alerts, daily logging reminders, weekly summaries, and updates on your savings challenges.
