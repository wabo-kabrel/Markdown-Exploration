# 📁 Relative Paths
## File Structure Example
my-project/  
├── README.md  
├── docs/  
│   ├── installation.md  
│   └── usage.md  
├── src/  
│   └── main.py  
├── assets/  
│   ├── images/  
│   │   └── logo.png  
│   └── videos/  
│       └── demo.mp4  
└── tests/  
    └── test_main.py  

## Linking to Files in Same Directory
[Installation Guide](installation.md)
[Usage Instructions](usage.md)

## Linking to Files in Subdirectories
[View Source Code](src/main.py)
[Run Tests](tests/test_main.py)

## Linking to Files in Parent Directory
[Back to Main README](../README.md)

## Images with Relative Paths
![Logo](assets/images/logo.png)
![Architecture Diagram](docs/images/architecture.png)

## Best Practices
 - Always use forward slashes / (works on all platforms)
 - Use relative paths for files within your repository
 - Use absolute URLs for external resources
 - Test your links by navigating through your repository