# Unhandled Network Errors in React Native

This example demonstrates a common error in React Native applications: unhandled network errors.  Improper error handling during network requests can result in app crashes or unexpected behavior. This repository shows how to correctly handle these errors.

## The Problem

The `DataList.js` file contains a component that fetches data from a remote API.  However, it lacks comprehensive error handling. If the API request fails (e.g., due to network issues or a server error), the app will likely crash or display a generic error message.

## The Solution

The `DataListSolution.js` file demonstrates the correct approach. It includes a `try...catch` block to handle potential errors during the fetch operation.  If an error occurs, the error message is caught and displayed to the user. Additionally, it handles loading states and ensures the app remains responsive even during network requests.