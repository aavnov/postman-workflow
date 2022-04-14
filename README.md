# Install dependencies
```
npm install  
```

# Install Newman
```
npm install -g newman
```

# Start the application
```
json-server --watch db.json --port 3004
```

# Run the postman tests
```
newman run "Postman Collections/albums.json"
```

