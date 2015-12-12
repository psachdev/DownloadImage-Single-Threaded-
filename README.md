# DownloadImage-Single-Threaded-
This was one of the many android assignments in which I was expected to implement the single threaded Image Download Service using Android Intent Service. 

# Features of this project 
1. The project is structured in accordance with Model-View-Presenter Pattern. It prevents re-initilization of the presenter layer upon runtime configuration change.
2. It's a single threaded download service - all the submitted image URLs to be dowloaded are queued and served one at a time.
3. Model layer is designed using the Bridge pattern. It helps to decouple the interface of the the model layer from the different types of download services used to implement this layer.

