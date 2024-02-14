# Vidhai: Farmer's Marketplace and Plant Disease Detection System

Vidhai is an application designed to facilitate farmers in connecting with fellow farmers and selling their produced goods directly to customers. Additionally, it integrates a plant disease detection system with a recommendation engine to suggest necessary remedies for curing detected diseases.

## Features
- **Farmer's Marketplace:** Farmers can create listings to sell their produce directly to customers.
- **Plant Disease Detection:** Utilizes a custom YOLOv8 model to detect plant diseases from images.
- **Recommendation Engine:** Provides recommendations for necessary remedies to cure detected plant diseases.
- **Flutter Application:** Built using the Flutter framework for cross-platform mobile applications.
- **Roboflow for Annotation:** Plant disease detection model training data annotated using Roboflow.
- **API Integration:** Connected to the frontend via API for seamless communication.

## Setup
1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd Vidhai`
3. Install dependencies: `flutter pub get`
4. Run the application: `flutter run`

## Model Training
1. Annotate images using Roboflow.
2. Train the custom YOLOv8 model using the annotated data.
3. Convert the trained model into a format compatible with Flutter.

## API Integration
- Ensure the backend API endpoints are correctly configured in the Flutter application.
- Use appropriate API calls to fetch data related to listings, plant diseases, and recommendations.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the [MIT License](LICENSE).
