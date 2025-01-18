# Web Service and WinForms Application

📝 **Project Description**
This project consists of two main components:

1. **CalculatorWS**: A web service that provides information about countries and cities.
2. **WinformWorld**: A Windows Forms application that consumes the web service to display information about countries and cities.

## 📂 **Project Structure**

### **CalculatorWS**
- **Data**: Contains the data required to process country and city information.
- **DataAccess**: Handles queries and data access.
- **Logic**: Contains the core business logic to handle requests from the web service.

### **WinformWorld**
- Contains user interface components to display and interact with data from CalculatorWS.

**CalculatorWS**: Contains the source code for a SOAP web service with methods to retrieve information about countries and cities.

**WinformWorld**: Contains the source code for a Windows Forms application with a user interface for inputting and displaying information from the web service.

## 🚀 **Setup and Run Instructions**

### Clone the repository:
```bash
git clone  https://github.com/PhamTrung1204/dbws.git
```

### Open the solution in Visual Studio:
1. Open the forder `DB_WS`.

### Build and run the web service:
1. Set **CalculatorWS** as the startup project.
2. Press `F5` to build and run the service.

### Configure and run the WinForms application:
1. Set **WinformWorld** as the startup project.
2. Open the file `Form1.cs` to review or customize the user interface.
3. Press `F5` to run the application.

## ⚙️ **Main Features**

### 🌍 **Web Service (CalculatorWS):**
Provides SOAP methods to retrieve information:
- **GetCityByName**: Takes a city name and returns detailed information about the city.
- **GetCitiesByCountry**: Takes a country code and returns a list of cities in that country.
- **GetAllCountries**: Returns a list of all countries.
- **GetCountryByCode**: Takes a country code and returns detailed information about the country.

### 💻 **WinForms Application (WinformWorld):**
A user-friendly interface that allows users to:
- Select a country from a list.
- Display a list of cities in the selected country.
- Send requests to the web service and display the results in the interface.

## 🛠️ **Workflow**

1. The user selects a country in the WinForms interface.
2. The WinForms application sends a request to the SOAP web service to retrieve the list of cities.
3. The web service returns the corresponding list of cities.
4. The application displays the list of cities to the user.

## 💾 **System Requirements**

### **Software:**
- Visual Studio 2022 or newer.
- .NET Framework supporting WinForms applications.

### **Hardware:**
- **Processor**: 1.6 GHz or higher.
- **RAM**: Minimum 2GB.
- **Free Disk Space**: Minimum 1GB.

## 📊 **Illustrative Examples**

### Request for country list:
- Interface displays the list of countries: Vietnam, United States, Japan.

### Request for city list:
- Selected country: Vietnam.
- Interface displays the list of cities: Hanoi, Ho Chi Minh City, Da Nang.

## 📚 **References**
- [Microsoft Docs: Create SOAP Services with ASP.NET](https://learn.microsoft.com)
- Guide to creating WinForms applications
