# Home Expense Manager

## Overview

**Home Expense Manager** is a simple and efficient Flutter-based application designed to help users manage their household expenses. Integrated with Firebase, this app allows users to set a monthly budget, distribute funds across various categories (such as groceries, utilities, and entertainment), and track their spending with detailed payment records. Any remaining funds are automatically carried over to the next month, ensuring a seamless financial management experience.

## Features

- **Monthly Budget Input:** Enter the available funds at the beginning of each month.
- **Category Allocation:** Distribute the monthly budget across customizable categories such as electricity, groceries, pocket money, gas, internet, and mobile.
- **Expense Tracking:** Log expenses within each category, including detailed descriptions of purchases.
- **Automatic Carryover:** Unused funds in each category are automatically carried over to the next month.
- **Real-time Sync:** All data is stored and synced in real-time using Firebase Firestore, ensuring access from multiple devices.
- **User Authentication:** Secure access to the app using Firebase Authentication (optional feature).

## Screenshots

## Installation

### Prerequisites

- **Flutter SDK**: Ensure you have Flutter installed on your machine. You can download it from the [Flutter website](https://flutter.dev/docs/get-started/install).
- **Firebase Account**: You'll need a Firebase account to set up the backend. You can sign up at [Firebase](https://firebase.google.com/).

### Steps to Install

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AhmedSaadKader/home-expense-manager.git
   cd home-expense-manager
   ```

2. **Install Dependencies:**

   ```bash
   flutter pub get
   ```

3. **Set Up Firebase:**

   - Create a new project in the [Firebase Console](https://console.firebase.google.com/).
   - Register your app (use the package name found in `android/app/src/main/AndroidManifest.xml`).
   - Download the `google-services.json` file and place it in the `android/app` directory.
   - Follow the setup steps outlined in [this guide](https://firebase.flutter.dev/docs/overview).

4. **Run the App:**
   ```bash
   flutter run
   ```

## Usage

- **Start a New Month:** Input the available funds at the beginning of the month.
- **Distribute Budget:** Allocate the budget across different categories as per your household needs.
- **Log Expenses:** As you spend, log each expense with details like date, amount, and description.
- **Review and Carry Over:** At the end of the month, review your spending, and the app will automatically carry over any unused funds to the next month.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or feature suggestions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, feel free to reach out:

- **Name:** Ahmed Saad Abd El-Kader
- **Email:** [ahmed.saad.kader@gmail.com](ahmed.saad.kader@gmail.com)
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/ahmed-saad-kader/)
