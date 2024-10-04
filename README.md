# AIAlchemists
This application is designed to optimize the supply chain process by providing both suppliers and buyers with intelligent, real-time recommendations. Leveraging the power of Intel oneAPI for faster and efficient computing, the app focuses on two main functionalities:

For Suppliers: It offers optimal delivery paths based on geographic data, real-time demand, and transportation costs, ensuring fast and cost-effective routes to deliver materials.
For Buyers: The app provides optimal recommendations on suppliers, helping buyers make data-driven decisions based on material price, availability, and delivery time.
Key Features:
Supplier Optimization: Calculates the most efficient delivery routes based on location, demand, and material specifics.
Buyer Recommendations: Suggests the best supplier options based on pricing, availability, and location proximity.
High-Performance Computing: Utilizes Intel oneAPI for faster calculations and model predictions, ensuring real-time optimization.
Machine Learning Integration: Incorporates ML models in TFLITE format for path optimization and supplier recommendations.
Technology Stack:
Frontend: Java with XML for Android.
Backend: Python with Intel oneAPI for model training and optimization.
Database: Firebase real-time database.
Machine Learning: TensorFlow Lite (TFLITE) models.
Usage:
Suppliers input material details, price, quantity, and location.
Buyers provide material requirements and location preferences.
The app processes this data to give the most efficient options for both parties.

How to Use the Application
1. Download and Install the APK (Android)
Download the APK file from the repository: Project_oneAPI_hack_kpr.apk.
Install the APK on your Android device by allowing installation from unknown sources (if prompted).
Open the app and follow the user prompts:

1.1. Suppliers: Enter material details, quantity, price, and location.
1.2. Buyers: Enter location, required material, and quantity.
The app will provide optimal delivery paths for suppliers and optimal material recommendations for buyers based on price and availability.

2. Clone the Repository (for Developers)
You can clone the repository to inspect and modify the codebase or datasets.

2.1. Clone via command line:
git clone https://github.com/ShashankS1011/AIAlchemists.git
(Or) 
2.2. download the repository directly as a ZIP file and extract it.

3. Datasets Used
The app leverages two datasets:

3.1. indian-cities-dataset.csv: Contains information on various Indian cities, used for geolocation and distance calculations.
3.2. Inventory.xlsx: Holds inventory details, including materials, quantities, and prices from different suppliers.
These datasets are used in the optimization process to provide real-time insights and recommendations.

4. Algorithms
The following algorithms have been implemented to power the optimization logic:

4.1. RankingPrice.ipynb: This algorithm ranks suppliers based on material price, availability, and buyer preferences.
4.2. ShortestPath.ipynb: This algorithm calculates the optimal path for suppliers to deliver materials, minimizing time and cost.
You can run these notebooks using Jupyter Notebook or Google Colab for a deeper understanding of the optimization techniques used in the app.

5. Running the Project Locally
If you want to modify or test the project locally:

Ensure you have Python and the required dependencies installed. You can install the dependencies by running:
pip install -r requirements.txt

Open the provided Jupyter notebooks to explore the algorithms:
RankingPrice.ipynb
ShortestPath.ipynb

