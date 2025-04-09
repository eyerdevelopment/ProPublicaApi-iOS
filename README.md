# ProPublicaCongressApp-iOS

An iOS app built using the ProPublica Congress API to display detailed information about U.S. legislators. The app customizes the user interface based on each legislator’s political party, offering a clean visual overview using live (or mock) data.

---

## Features

- Displays member data: name, title, party, state, and portrait
- Dynamic UI changes based on party affiliation (Republican, Democrat, Independent)
- Uses a custom model object (`ProPublicaData`) to manage parsed JSON data
- Updates interface labels and image views programmatically
- Built with UIKit and storyboard-based layout

---

## API Access Note

This project was built using the [ProPublica Congress API](https://www.propublica.org/datastore/api/propublica-congress-api). While the API is still available, this app’s access key is no longer active and they do not offer new ones. As a result, live data cannot currently be fetched. However, the architecture remains fully functional and demonstrates authentication setup, UI binding, and structured data handling.

---

## Built With

- Swift 5
- UIKit
- URLSession (for network calls)
- JSON parsing (manual/custom model)
- Interface Builder + Storyboards

---

## Author

Sarah Meyer 
Originally built for CE05 at Full Sail University  
Updated in 2025 for professional portfolio use
