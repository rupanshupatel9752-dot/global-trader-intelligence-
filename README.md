# Global Trader Intelligence

An Android market dashboard starter for traders. The app uses a native Android WebView shell and TradingView's public embeddable widgets for market charts and market overview.

## Build an APK without Android Studio

1. Open the **Actions** tab in this repository.
2. Select **Build Android APK**.
3. Tap **Run workflow** and confirm.
4. Wait for the workflow to finish successfully.
5. Open the completed run and download the **Global-Trader-Intelligence-debug-APK** artifact.

The APK is a debug build for testing and direct installation. A Play Store release needs a signed release build, app icon, privacy policy, and store listing.

## Data and limitations

- Market widgets are provided by TradingView and require an internet connection.
- Quotes, chart availability, exchange coverage, and delays depend on the embedded provider and exchange licensing.
- This starter does not claim to provide exchange-grade real-time NSE/MCX data, FII/DII live positions, or investment advice.
- Do not enter broker passwords, API secrets, or financial account credentials in this app.

## Project

- Android app: `app/`
- Dashboard page: `app/src/main/assets/index.html`
- Automated APK build: `.github/workflows/android-apk.yml`
