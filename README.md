This Java-based application assesses the efficiency of various vehicle types, including hybrid, gasoline, and electric vehicles. It defines interfaces for different vehicle categories and conducts unit tests to evaluate the functionality of a hybrid vehicle.

### Project Structure:

- **src/main/java:** Contains the main application code, which includes the following files:
  - **App.java:** The entry point of the application.
  - **CarRunner.java:** Executes various vehicle types and compares their efficiencies.
  - **ElectricInterface.java:** Defines the interface for electric vehicles.
  - **GasolineInterface.java:** Specifies the interface for gasoline-powered vehicles.
  - **Hybrid.java:** Implements functionality unique to hybrid vehicles.
  - **HybridVehicle.java:** Models the hybrid vehicle, integrating features from both electric and gasoline vehicles.
  
- **src/test/java:** Contains unit tests for the application.
  - **AppTest.java:** Unit tests for the overall application logic.
  - **HybridTest.java:** Unit tests for the Hybrid class to ensure the correct functionality of the hybrid vehicle model.

### How to Build and Run:

1. Clone the repository.
2. Run the following commands:
   - `mvn compile`
   - `mvn clean test`
