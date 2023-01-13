# 💲 DuniPool
A simple application to know Diagital Currency as online.

# 📚 Used
Android View, Kotlin-Parcelize, Retrofit2, RecyclerView, Spark-Chart, Sipe-Refresh, Glide, ...

# 📑 Dependency
Add below codes to `build.gradle(:app)`:

  in `plugins` part:
   
    id 'kotlin-parcelize'

  in `android` part:
    
    buildFeatures {
      viewBinding true
    }
      
   in `dependencies` part:
    
   `Retrfot2`:
   
    def retrofit2_version = "2.9.0"
    implementation "com.squareup.retrofit2:retrofit:$retrofit2_version"
    implementation "com.squareup.retrofit2:converter-gson:$retrofit2_version"
    
   `Show Chart(SparkView)`:
   
     implementation 'com.robinhood.spark:spark:1.2.0'
     
   `Show Refresh-action(SwipeRefresh)`:
    
     implementation 'androidx.swiperefreshlayout:swiperefreshlayout:1.1.0'
     
   `show/load images(Glide)`:
     
     implementation 'com.github.bumptech.glide:glide:4.13.2'
     annotationProcessor 'com.github.bumptech.glide:compiler:4.13.2'
     
# 📝 Usesage
to update, check, make change you can go to `master` branch
     
# ✨ View :-)

![Uploading img_show1.jpg…]()
![Uploading img_show2.jpg…]()

![Uploading img_show3.jpg…]()
![Uploading img_show5.jpg…]()



