# Android
Thing to Read or Know in Android

-Butter Knife library: To remove findViewById in code

  in kotlin it's enough to add following code to app gradle:
      androidExtensions{
            experimental = true
                }

-AndroidAnnotation: Open source framework for android development by Java

-Retrofit: Library to call webservices

-Add following to build.gradle when you want to use lambda:

compileOptions {

sourceCompatibility JavaVersion.VERSION_1_8

targetCompatibility JavaVersion.VERSION_1_8

}

-BaseActivity: Always create a BaseActivity class that extends AppCompatActivity.
  then App activities extends this BaseActivity useful for avoid repeatetive code like when you use Hawk

-BaseApplication: this class extends Application class. this class is called before activities.
  
-LeakCanary: A library to detect memory leaks in android
  
-Test

    1. BlackBox Test: by end user
    2. WhiteBox Test
        2.1. by developer
        2.2. Unit Test: just for testing plain java & kotlin codes
          2.3. TDD (Test Driven Development)
         
