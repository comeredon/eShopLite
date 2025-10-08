# eShopLite

A lightweight e-commerce application built with ASP.NET Core and Blazor.

## Repository

🔗 **GitHub Repository:** [https://github.com/comeredon/eShopLite](https://github.com/comeredon/eShopLite)

## Project Structure

This solution contains:
- **DataEntities**: Shared data models and entities
- **Products**: ASP.NET Core Web API for product management
- **Store**: Blazor Server application for the storefront

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/comeredon/eShopLite.git
   ```

2. Navigate to the project directory:
   ```bash
   cd eShopLite
   ```

3. Build and run the solution:
   ```bash
   dotnet build
   dotnet run --project Products
   dotnet run --project Store
   ```