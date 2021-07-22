# Location History

Built using XCode 12.5

### How to run the project?

1. Clone this repo
1. Open shell window and navigate to project folder
1. Run `pod install`
1. Open `location-history.xcworkspace` and run the project on selected device or simulator


### How to create an API key?

1. Go to the Google Maps Platform > Credentials page.
1. Go to the [Credentials page](https://console.cloud.google.com/project/_/google/maps-apis/credentials?_ga=2.43024097.577050595.1626929752-249147691.1626929752)
1. On the Credentials page, click Create credentials > API key.
The API key created dialog displays your newly created API key.
Click Close.
1. The new API key is listed on the Credentials page under API keys.
(Remember to restrict the API key before using it in production.)
1. Enable Places API from console for the selected project.
1. Enable Billing for the selected project.
1. Copy the API key and paste it in the `AppDelegate.swift` file by replacing `YOUR_API_KEY`.

