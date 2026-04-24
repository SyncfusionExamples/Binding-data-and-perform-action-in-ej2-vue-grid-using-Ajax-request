# Bind EJ2 Vue Grid to Data via Ajax Requests

## Repository Description
A demonstration of Syncfusion EJ2 Grid in Vue with Ajax-based data binding for CRUD operations.

## Overview
This example shows how to use the EJ2 Grid with Ajax requests in Vue for seamless CRUD operations.

## Project Structure

### Client (ajaxproject.client)
Vue 3 app with Syncfusion EJ2 Grid, Ajax data binding, and CRUD operations via server calls.

### Server (AjaxProject.Server)
ASP.NET Core Web API with HomeController handling Getdata, Insert, Update, Delete operations.

## Features
- EJ2 Grid with paging and editing
- Ajax data binding
- CRUD via Ajax
- ASP.NET Core backend

## Prerequisites
- Node.js and npm
- .NET 8.0 SDK

## Installation

### Client
```
git clone https://github.com/SyncfusionExamples/Binding-data-and-perform-action-in-ej2-vue-grid-using-Ajax-request
cd Binding-data-and-perform-action-in-ej2-vue-grid-using-Ajax-request\AjaxProject\ajaxproject.client
npm install
```

### Server
```
cd AjaxProject.Server
dotnet restore
```

## Running the Application

1. Start the backend server:
```
cd AjaxProject.Server
dotnet run
```

2. Start the Vue dev server:
```
cd ajaxproject.client
npm run dev
```

3. Click "Bind data via ajax" button to load data

## Examples

EJ2 Grid demos:

https://ej2.syncfusion.com/vue/demos/#/tailwind3/grid/localdata

https://ej2.syncfusion.com/vue/demos/#/tailwind3/grid/remote-data

## Documentation

https://ej2.syncfusion.com/vue/documentation/grid/data-binding/
