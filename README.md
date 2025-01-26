# Navigation Drawer

This repository contains the source code for an Android application demonstrating the implementation of a Navigation Drawer using the Kotlin language within the Android Studio environment. This project showcases how to create a user-friendly and intuitive navigation experience.

<hr><br>

## Purpose of This Repository

To showcase the integration of a Navigation Drawer with Fragments to create a flexible and modular user interface within an Android application developed with Kotlin.

<hr><br>

## Demo

### Program Function Demonstration

```kotlin
// filepath: /home/guan/Documents/Code/Navigation-Drawer/app/src/main/java/com/example/navigationdrawer/MainActivity.kt
// ...existing code...
class MainActivity : AppCompatActivity() {
    // ...existing code...
    private fun setupDrawer() {
        val drawerLayout: DrawerLayout = findViewById(R.id.drawer_layout)
        val navView: NavigationView = findViewById(R.id.nav_view)
        val toggle = ActionBarDrawerToggle(
            this, drawerLayout, toolbar, R.string.navigation_drawer_open, R.string.navigation_drawer_close
        )
        drawerLayout.addDrawerListener(toggle)
        toggle.syncState()
        navView.setNavigationItemSelectedListener(this)
    }
    // ...existing code...
}
```

<hr><br>

## Releases

You can find the latest releases [here](https://github.com/guanshiyin28/Navigation-Drawer/releases).

<hr><br>

## Features

- Navigation Drawer with multiple menu items
- Fragment integration
- Responsive and intuitive UI
- Easy to navigate

<hr><br>

## Technologies Used

- Kotlin
- Android Studio
- XML for layout design

<hr><br>

## Project Setup

1. **Clone this Repository**

```bash
git clone https://github.com/guanshiyin28/Navigation-Drawer.git
```

2. **Open the project in Android Studio**
3. **Sync the project with Gradle files**
4. **Build the project**

<hr><br>

## Steps to Run

1. **Connect an Android device or start an emulator**
2. **Run the project from Android Studio**

<hr><br>

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.

<hr><br>

<div align="center">
   <a href="https://www.instagram.com/guanshiyin_/">
      <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=100:393E46,20:F7F7F7&section=footer&reversal=false&textBg=false&fontAlignY=50&descAlign=48&descAlignY=59"/>
   </a>
</div>
