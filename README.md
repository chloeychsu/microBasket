# microBasket
microBasket is a shopping cart web application using Microservice Architecture 

# Architecture
![](./architecture.drawio.svg)


# Development Note

```csharp
dotnet new sln -n micro-basket -o src
dotnet new webapi -o src/AuctionService --use-controllers
dotnet sln add src/AuctionService 
```