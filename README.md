
# Daily Image App

This app fetches the daily image published by NASA and it's details from NASA Api and displays on UI.

## API Reference

#### NASA API

```http
  GET https://api.nasa.gov/planetary/apod?api_key=
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | KGjXKB7oThqzroew0HHS0aK0vuOhTg4pjNiGkUhV |




## Deployment
1. Used Retrofit Library for API call request.
2. Stored the response received by successful API call in Shared Preferences.
3. Fetchch the cached data and display it on UI.
4. Used Glide library for loading image from URL.
5. Followed MVVM Architecture for project structuring.




## Installation 
Steps to run this app -
1. Clone this project from GitHub Repository - "https://github.com/shubhamsingh611/MyNoteBookApp"
2. Run the project in Android Studio
Top Menu -> Run -> Run App

## Authors

- [@shubhamsingh611](https://www.github.com/shubhamsingh611)

