## Simple experiment with typescript and google maps API

- [Typescript](https://www.typescriptlang.org/)
- [Maps Javascript API](https://developers.google.com/maps/documentation/javascript/overview)
- [Parcel Bundler](https://www.npmjs.com/package/parcel-bundler)
- [Faker](https://www.npmjs.com/package/faker)

# Commands

Start the application locally

```
parcel index.html
```

# Note

1. Make sure that you change add your API key in the index.html script

```
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script>
```

Refer to [Google Developer Console](https://developers.google.com/maps/documentation/javascript/overview)

2. This app uses specific version of faker and its types

```
"faker": "^5.5.3"
"@types/google.maps": "^3.47.4",
```
