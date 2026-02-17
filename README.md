<div align="center">

<!-- Banner with improved text visibility -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=300&section=header&text=EasyAds%20SDK&fontSize=80&fontAlignY=28&desc=Monetize%20Smarter%2C%20Code%20Faster%20%7C%20The%20Ultimate%20Android%20Ad%20Integration&descAlignY=52&descSize=22&animation=twinkling" />

<br/>

<!-- Badges Row -->
<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-Compatible-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Min%20SDK-21-00ADD8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" />
</p>

[//]: # (<p align="center">)

[//]: # (  <a href="#-why-choose-us">Why Choose</a> •)

[//]: # (  <a href="#-quick-start">Quick Start</a> •)

[//]: # (  <a href="#-ad-formats">Ad Formats</a> •)

[//]: # (  <a href="#-showcase">Showcase</a> •)

[//]: # (  <a href="#-future-roadmap">Future Roadmap</a> •)

[//]: # (  <a href="#-community">Community</a>)

[//]: # (</p>)

<h2>🚀 The Ultimate AdMob Wrapper for Android Developers</h2>
<p><i>Integrate AdMob in minutes, not hours. One SDK, infinite monetization possibilities.</i></p>

<br/>

<!-- Stats -->

[//]: # (<p align="center">)

[//]: # (  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/EasyAds?style=social" />)

[//]: # (  <img src="https://img.shields.io/github/forks/YOUR_USERNAME/EasyAds?style=social" />)

[//]: # (  <img src="https://img.shields.io/github/watchers/YOUR_USERNAME/EasyAds?style=social" />)

[//]: # (  <img src="https://img.shields.io/github/issues/YOUR_USERNAME/EasyAds?style=social" />)

[//]: # (</p>)

</div>

<br/>

---

## 🎯 Why Choose EasyAds?

<div align="center">

### ✨ Three Pillars of Excellence

<table>
<tr>
<td align="center" width="33%">

### 🎨 **Beautiful**

<img src="https://img.shields.io/badge/Customization-100%25-success?style=for-the-badge" />

Fully customizable native ads that blend seamlessly with your app's design. Match colors, fonts, and layouts perfectly.

</td>
<td align="center" width="33%">

### ⚡ **Lightning Fast**

<img src="https://img.shields.io/badge/Performance-Optimized-blue?style=for-the-badge" />

Minimal impact on app size and speed. Optimized for performance with smart preloading and memory management.

</td>
<td align="center" width="33%">

### 🛠️ **Feature Rich**

<img src="https://img.shields.io/badge/Ad%20Formats-5+-orange?style=for-the-badge" />

5 ad formats, Pro version support, comprehensive listeners, and automatic Ad-Free handling built-in.

</td>
</tr>
</table>

</div>

<br/>

<div align="center">

### 🔥 **See The Difference**

| 😫 Traditional Approach | 😍 With EasyAds SDK |
|-------------------------|---------------------|
| ❌ 200+ lines of boilerplate code | ✅ **Just 3 lines** to load ads |
| ❌ Complex integration process | ✅ **Copy-paste ready** implementation |
| ❌ Boilerplate hell everywhere | ✅ **Clean architecture** throughout |
| ❌ Memory leaks are common | ✅ **Auto memory management** |
| ❌ Manual Pro/Ad-Free handling | ✅ **Automatic Pro detection** |
| ❌ Repetitive listener setup | ✅ **Unified listener system** |

</div>

<br/>

---

## ⚡ Quick Start

### 📦 Step 1: Add JitPack Repository

Add JitPack to your **project-level** `settings.gradle` or `build.gradle`:

```gradle
repositories {
    google()
    mavenCentral()
}
```

### 📚 Step 2: Add Dependencies

Add these dependencies to your **app-level** `build.gradle`:

```gradle
dependencies {
    // EasyToUse AdMob SDK
    implementation "io.github.easydev13:quickads-admob:1.0.1"
}
```

### 🧠 Step 3: Initialize SDK (Required)

Initialize the SDK in your **Application** class:

```kotlin
class MyApp : Application() {

    override fun onCreate() {
        super.onCreate()

        // Initialize EasyAd SDK
        EasyAdSdk.initialize(
            context = this,
            isDebug = true  // Set to false for production
        )

        // Optional: Enable Ad-Free / Pro version
        // EasyAdsConfig.enableProFeatures()
    }
}
```

**Don't forget to add your Application class to `AndroidManifest.xml`:**

```xml
<application
    android:name=".MyApp"
    ...>
```

### 🎬 Step 4: Load Your First Ad

```kotlin
// Banner Ad - Just 3 lines!
val bannerView = findViewById<EasyBannerView>(R.id.easyBannerView)
bannerView.load(
    adUnitId = "ca-app-pub-3940256099942544/6300978111",
    listener = object : EasyBannerListener {
        override fun onAdLoaded() { Log.d("Banner", "✅ Loaded!") }
        override fun onAdFailed(error: String) { Log.e("Banner", "❌ $error") }
        override fun onAdClicked() { Log.d("Banner", "🔗 Clicked!") }
    }
)
```

<div align="center">

### 🎉 That's it! You're ready to monetize! 🎉

[//]: # (### 🎥 [Watch Video Tutorial]&#40;#&#41; • 📖 [Read Full Docs]&#40;#&#41; • 💬 [Get Help]&#40;#&#41;)

</div>

<br/>

---

<div align="center">

# 🎪 Ad Formats

</div>

<br/>

<!-- Banner Ads Section -->
<details open>
<summary><h2>🏷️ Banner Ads - Always Visible Revenue</h2></summary>

<br/>

### 📊 Performance Stats

| Metric | Value |
|--------|-------|
| **Fill Rate** | 95% |
| **Average CTR** | 2.5% |
| **eCPM Range** | High |
| **Load Time** | < 1 second |
| **User Impact** | Low (Non-intrusive) |

<br/>

### 💡 When to Use

Banner ads are perfect for continuous ad presence without disrupting user experience:

- ✅ **Bottom of screen placement** - Persistent visibility without blocking content
- ✅ **Between content sections** - Natural breaks in scrollable content
- ✅ **Inside scrollable lists** - Integrated within RecyclerView/ListView
- ✅ **Persistent revenue stream** - Always-on monetization strategy

<br/>

### 📝 Implementation

#### Step 1: Add to Layout

```xml
<!-- Add EasyBannerView to your XML layout -->
<com.easyads.admobads.banner.EasyBannerView
    android:id="@+id/easyBannerView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"/>
```

#### Step 2: Load Banner

```kotlin
val bannerView = findViewById<EasyBannerView>(R.id.easyBannerView)

bannerView.load(
    adUnitId = "ca-app-pub-3940256099942544/6300978111",
    listener = object : EasyBannerListener {
        override fun onAdLoaded() {
            Log.d("BannerAd", "💰 Banner loaded successfully!")
        }
        
        override fun onAdFailed(error: String) {
            Log.e("BannerAd", "⚠️ Failed to load: $error")
        }
        
        override fun onAdClicked() {
            Log.d("BannerAd", "🔗 User clicked banner!")
        }
    }
)
```

#### 🔒 Ad-Free Behavior

If user is Pro → banner will not load or auto hide automatically!

```kotlin
// Enable Pro/Ad-Free mode
EasyAdsConfig.enableProFeatures()
```

<br/>

### 🎯 Best Practices

| ✅ Do | ❌ Don't |
|-------|----------|
| Place at screen bottom for maximum visibility | Stack multiple banners on same screen |
| Refresh ads every 30-60 seconds | Refresh too frequently (< 30 seconds) |
| Match banner colors with app theme | Use default colors that clash with UI |
| Keep banner visible during user interaction | Hide/show banner repeatedly |

<br/>

### 📖 Official Documentation

- [Google AdMob Banner Ads Guide](https://developers.google.com/admob/android/banner)
- [Banner Ad Sizes](https://developers.google.com/admob/android/banner/size)
- [Banner Best Practices](https://support.google.com/admob/answer/6128877)

</details>

<br/>

<!-- Interstitial Ads Section -->
<details>
<summary><h2>🎬 Interstitial Ads - Full-Screen Impact</h2></summary>

<br/>

### 📊 Performance Stats

| Metric | Value |
|--------|-------|
| **Fill Rate** | 90% |
| **Average CTR** | 5-8% |
| **eCPM Range** | Very High |
| **Load Time** | 2-3 seconds |
| **User Impact** | Medium (Intrusive) |

<br/>

### 💡 When to Use

Full-screen ads shown at natural transition points in your app:

- ✅ **Level Complete** - After finishing a game level or stage
- ✅ **Article Read** - After user finishes reading content
- ✅ **Between Activities** - During natural navigation transitions
- ✅ **Time-Based** - After certain time intervals (e.g., every 3 minutes)
- ❌ **Settings Open** - Never interrupt utility functions
- ❌ **Purchase Flow** - Never block monetization actions
- ⚠️ **App Launch** - Use sparingly, only after 2nd or 3rd launch

<br/>

### 🎯 Perfect Timing Guide

| App Flow Scenario | Show Interstitial? |
|-------------------|-------------------|
| 🎮 Level Complete | ✅ YES! (High engagement moment) |
| 📄 Article Finished | ✅ YES! (Natural break point) |
| 🏠 Home → Settings | ❌ NO (Utility navigation) |
| 💳 Checkout Process | ❌ NO (Never block revenue) |
| 🎵 Song Completed | ✅ YES! (Natural transition) |
| ⚙️ Settings Changed | ❌ NO (Quick actions) |
| 📱 App Launch | ⚠️ MAYBE (After 2-3 launches) |

<br/>

### 📝 Implementation

#### Step 1: Initialize Interstitial

```kotlin
class MainActivity : AppCompatActivity() {
    private lateinit var interstitial: EasyInterstitialAd
    
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        
        // Initialize
        interstitial = EasyInterstitialAd(
            this, 
            "ca-app-pub-3940256099942544/1033173712"
        )
        
        setupListener()
        interstitial.load()
    }
}
```

#### Step 2: Setup Listener

```kotlin
private fun setupListener() {
    interstitial.setListener(object : EasyInterstitialListener {
        override fun onAdLoaded() {
            Log.d("Interstitial", "✅ Ad ready to show!")
        }
        
        override fun onAdFailed(error: String) {
            Log.e("Interstitial", "❌ Failed: $error")
        }
        
        override fun onAdClosed() {
            Log.d("Interstitial", "🔄 User closed ad")
            // Preload next ad
            interstitial.load()
        }
    })
}
```

#### Step 3: Show Ad

```kotlin
// Show when ready
fun onLevelComplete() {
    interstitial.showIfAvailable()
    // Continues to next screen automatically if ad not ready
}
```

<br/>

### 🎯 Best Practices

| ✅ Do | ❌ Don't |
|-------|----------|
| Preload ads during app initialization | Load ad right before showing |
| Show at natural transition points | Interrupt active user tasks |
| Use `showIfAvailable()` for safety | Show without checking availability |
| Reload ad immediately after closing | Wait too long to reload next ad |
| Show every 3-5 user actions | Show every action (too frequent) |

<br/>

### 📖 Official Documentation

- [Google AdMob Interstitial Ads Guide](https://developers.google.com/admob/android/interstitial)
- [Interstitial Best Practices](https://support.google.com/admob/answer/6066980)
- [Ad Frequency Capping](https://support.google.com/admob/answer/7665432)

</details>

<br/>

<!-- Rewarded Ads Section -->
<details>
<summary><h2>🎁 Rewarded Ads - Win-Win Monetization</h2></summary>

<br/>

### 📊 Performance Stats

| Metric | Value |
|--------|-------|
| **Completion Rate** | 90%+ |
| **Average CTR** | 8-12% |
| **eCPM Range** | Highest |
| **Load Time** | 3-4 seconds |
| **User Satisfaction** | 85% ⭐⭐⭐⭐⭐ |

<br/>

### 💡 When to Use

Rewarded ads create a win-win scenario where users opt-in to watch ads in exchange for valuable rewards:

**🎮 Gaming:**
- Extra lives or continues
- Power-ups and boosters
- In-game currency (coins, gems)
- Unlock special levels
- Skip waiting timers

**🎵 Music & Media:**
- Skip ads for free users
- Unlock premium songs
- HD/4K streaming quality
- Offline downloads
- Remove watermarks

**📚 Education:**
- Premium lessons access
- Unlock hints/solutions
- Extra practice questions
- Certificate downloads
- Ad-free study time

**🎬 Video Streaming:**
- Watch premium content
- HD quality upgrade
- Early access to episodes
- Skip intro/outro
- Download for offline

**💪 Fitness & Health:**
- Advanced workout plans
- Personalized diet plans
- Pro training videos
- Meal tracking features
- Progress analytics

<br/>

### 📈 Why Rewarded Ads Win

| Traditional Ads | Rewarded Ads |
|-----------------|--------------|
| ❌ Forced interruption | ✅ User choice & control |
| 😠 User annoyance | 😊 User satisfaction |
| 📉 Low engagement | 📈 High engagement (90%+) |
| ⏭️ 80% skip rate | ✅ 90%+ completion rate |
| 💸 Lower eCPM | 💰 2x higher eCPM |
| 😤 Negative perception | 🎁 Positive value exchange |

<br/>

### 📝 Implementation

#### Step 1: Initialize Rewarded Ad

```kotlin
class RewardManager(private val activity: Activity) {
    
    private val rewardedAd = EasyRewardedAd(
        activity,
        "ca-app-pub-3940256099942544/5224354917"
    )
    
    init {
        setupListener()
        rewardedAd.load()
    }
}
```

#### Step 2: Setup Listener

```kotlin
private fun setupListener() {
    rewardedAd.setListener(object : EasyRewardedListener {
        
        override fun onAdLoaded() {
            Log.d("Rewarded", "✅ Ad loaded!")
            showRewardButton() // Enable button
        }
        
        override fun onAdFailed(error: String) {
            Log.e("Rewarded", "❌ Failed: $error")
            hideRewardButton()
        }
        
        override fun onRewardEarned(amount: Int, type: String) {
            Log.d("Rewarded", "🎉 Earned: $amount $type")
            // Grant reward to user
            grantUserReward(amount, type)
            showThankYouMessage()
        }
        
        override fun onAdClosed() {
            Log.d("Rewarded", "🔄 Ad closed")
            rewardedAd.load() // Preload next
        }
    })
}
```

#### Step 3: Show Rewarded Ad

```kotlin
fun showRewardedAd() {
    rewardedAd.showIfAvailable()
}
```

#### Step 4: Grant Rewards

```kotlin
private fun grantUserReward(amount: Int, type: String) {
    // Example: Grant coins
    UserData.coins += amount
    UserData.save()
    
    // Update UI
    updateCoinDisplay()
    showRewardAnimation()
}

private fun showThankYouMessage() {
    Toast.makeText(
        activity,
        "🎉 You've earned 100 coins! Thanks for watching!",
        Toast.LENGTH_SHORT
    ).show()
}
```

<br/>

### 🎯 Best Practices

| ✅ Do | ❌ Don't |
|-------|----------|
| Always preload ads in advance | Load ad when user clicks button |
| Show clear reward description | Use vague "Watch ad" text |
| Make watching completely optional | Force users to watch ads |
| Grant rewards immediately after completion | Delay reward delivery |
| Thank users for watching | Ignore user's contribution |
| Provide valuable, meaningful rewards | Offer trivial/useless rewards |
| Show reward amount before playing | Hide what user will get |

<br/>

### 💡 Pro Tips

```kotlin
// TIP 1: Show reward amount in button
button.text = "Watch Ad & Get 100 Coins 🎁"

// TIP 2: Use showIfAvailable() for safety
rewardedAd.showIfAvailable()

// TIP 3: Track completion rate (aim for 90%+)
val completionRate = (completions / impressions) * 100
```

<br/>

### 📖 Official Documentation

- [Google AdMob Rewarded Ads Guide](https://developers.google.com/admob/android/rewarded)
- [Rewarded Ads Best Practices](https://support.google.com/admob/answer/9884467)
- [Server-Side Verification](https://developers.google.com/admob/android/ssv)

</details>

<br/>

<!-- Native Ads Section -->
<details>
<summary><h2>🎨 Native Ads - Seamless Integration Master</h2></summary>

<br/>

### 📊 Performance Stats

| Metric | Value |
|--------|-------|
| **Fill Rate** | 92% |
| **Average CTR** | 4-6% |
| **eCPM Range** | High |
| **Load Time** | 2-3 seconds |
| **User Experience** | Excellent ⭐⭐⭐⭐⭐ |

<br/>

### 💡 When to Use

Native ads blend seamlessly with your app's content, providing the best user experience:

- ✅ **Social Media Feeds** - Instagram/Facebook style in-feed placement
- ✅ **News/Article Lists** - Blend with content cards
- ✅ **E-commerce Grids** - Match product listing style
- ✅ **Video Feed** - YouTube/TikTok style native placement
- ✅ **Search Results** - Integrate with search listings
- ✅ **Recipe/Blog Apps** - Match content card design

<br/>

### 🎭 Four Template Sizes

| Template | Size | Best For |
|----------|------|----------|
| **📱 SMALL** | `gnt_small_template_view` | Lists, compact feeds, sidebars |
| **📄 MEDIUM** | `gnt_medium_template_view` | Content grids, standard feeds |
| **📰 LARGE** | `gnt_large_template_view` | Featured content, article cards |
| **🖼️ FULLSCREEN** | `gnt_fullscreen_template_view` | Between screens, full-page transitions |

<br/>

### 📝 Implementation

#### Step 1: Add Template View to Layout

```xml
<!-- Add EasyTemplateView to your XML layout -->
<com.easyads.admobads.nativead.EasyTemplateView
    android:id="@+id/easyTemplateView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:gnt_template_type="@layout/gnt_medium_template_view"/>
```

**Available Templates:**
- `@layout/gnt_small_template_view`
- `@layout/gnt_medium_template_view`
- `@layout/gnt_large_template_view`
- `@layout/gnt_fullscreen_template_view`

#### Step 2: Customize Style (Optional)

```kotlin
val templateView = findViewById<EasyTemplateView>(R.id.easyTemplateView)

// Create custom style
val style = NativeTemplateStyle.Builder()
    // Text styling
    .withPrimaryTextSize(16f)
    .withPrimaryTextTypefaceColor(Color.BLACK)
    .withSecondaryTextSize(14f)
    .withSecondaryTextTypefaceColor(Color.GRAY)
    
    // Button styling
    .withCallToActionBackgroundColor(ColorDrawable(Color.BLUE))
    .withCallToActionTextSize(14f)
    .withCallToActionTextTypefaceColor(Color.WHITE)
    
    // Background
    .withMainBackgroundColor(ColorDrawable(Color.WHITE))
    
    .build()

// Apply style BEFORE loading ad
templateView.setStyles(style)
```

#### Step 3: Load Native Ad

```kotlin
val nativeLoader = EasyNativeAdLoader(
    this, 
    "ca-app-pub-3940256099942544/2247696110"
)

nativeLoader.setListener(object : EasyNativeAdListener {

    override fun onAdLoaded(nativeAd: NativeAd) {
        Log.d("NativeAd", "✅ Ad loaded successfully!")
        // Ad is automatically set in template view
        templateView.setNativeAd(nativeAd)
    }

    override fun onAdFailedToLoad(errorMessage: String) {
        Log.e("NativeAd", "❌ Failed: $errorMessage")
        // Hide ad container
        templateView.visibility = View.GONE
    }

    override fun onAdClicked() {
        Log.d("NativeAd", "🔗 User clicked ad!")
    }
})

nativeLoader.loadNativeAd()
```

#### Step 4: Destroy Ad (IMPORTANT!)

```kotlin
override fun onDestroy() {
    // Always destroy native ads to prevent memory leaks
    templateView.destroyNativeAd()
    super.onDestroy()
}
```

<br/>

### 🎨 Full Customization Options

#### 📝 Text Styling
```kotlin
.withPrimaryTextSize(18f)              // Headline text size
.withPrimaryTextTypefaceColor(color)   // Headline color
.withSecondaryTextSize(14f)            // Body text size
.withSecondaryTextTypefaceColor(color) // Body text color
.withTertiaryTextSize(12f)             // Advertiser text size
.withTertiaryTextTypefaceColor(color)  // Advertiser color
```

#### 🎨 Colors & Layout
```kotlin
.withMainBackgroundColor(ColorDrawable(color))        // Card background
.withCallToActionBackgroundColor(ColorDrawable(color)) // Button background
.withCallToActionTextTypefaceColor(color)             // Button text color
.withCornerRadius(8)                                   // Card corner radius
```

<br/>

### 🎯 Advanced: RecyclerView Integration

```kotlin
class FeedAdapter : RecyclerView.Adapter<RecyclerView.ViewHolder>() {
    
    companion object {
        const val VIEW_TYPE_CONTENT = 0
        const val VIEW_TYPE_NATIVE_AD = 1
        const val AD_FREQUENCY = 5 // Show ad every 5 items
    }
    
    override fun getItemViewType(position: Int): Int {
        return if (position % AD_FREQUENCY == 0 && position != 0) {
            VIEW_TYPE_NATIVE_AD
        } else {
            VIEW_TYPE_CONTENT
        }
    }
    
    inner class NativeAdViewHolder(view: View) : RecyclerView.ViewHolder(view) {
        private val templateView: EasyTemplateView = 
            view.findViewById(R.id.easyTemplateView)
        
        fun bind() {
            val loader = EasyNativeAdLoader(
                itemView.context,
                "YOUR_NATIVE_AD_UNIT_ID"
            )
            
            loader.setListener(object : EasyNativeAdListener {
                override fun onAdLoaded(nativeAd: NativeAd) {
                    templateView.setNativeAd(nativeAd)
                    templateView.visibility = View.VISIBLE
                }
                
                override fun onAdFailedToLoad(errorMessage: String) {
                    templateView.visibility = View.GONE
                }
            })
            
            loader.loadNativeAd()
        }
    }
    
    // Important: Clean up in RecyclerView
    override fun onViewRecycled(holder: RecyclerView.ViewHolder) {
        if (holder is NativeAdViewHolder) {
            holder.templateView.destroyNativeAd()
        }
        super.onViewRecycled(holder)
    }
}
```

<br/>

### 🎯 Best Practices

| ✅ Do | ❌ Don't |
|-------|----------|
| Match native ad style with your content | Use default styling that stands out |
| Set styles BEFORE loading ad | Apply styles after ad is loaded |
| Show native ads every 4-6 content items | Show ad after every item (too frequent) |
| Always destroy ads in onDestroy() | Forget to clean up (memory leaks!) |
| Hide ad container if load fails | Show empty container on failure |
| Use appropriate template size for placement | Use FULLSCREEN in small list items |

<br/>

### 📖 Official Documentation

- [Google AdMob Native Ads Guide](https://developers.google.com/admob/android/native/start)
- [Native Ads Advanced](https://developers.google.com/admob/android/native/advanced)
- [Native Ad Templates](https://developers.google.com/admob/android/native/templates)
- [Native Ads Best Practices](https://support.google.com/admob/answer/6329638)

</details>

<br/>

<!-- Rewarded Interstitial Ads Section -->
<details>
<summary><h2>💎 Rewarded Interstitial Ads - Best of Both Worlds</h2></summary>

<br/>

### 📊 Performance Stats

| Metric | Value |
|--------|-------|
| **Completion Rate** | 85%+ |
| **Average CTR** | 6-10% |
| **eCPM Range** | Very High |
| **Load Time** | 2-4 seconds |
| **User Experience** | Good ⭐⭐⭐⭐ |

<br/>

### 💡 When to Use

Rewarded Interstitial ads combine the immersive full-screen format with optional user rewards:

- ✅ **Game Over Screen** - Offer continue with reward
- ✅ **Content Unlock** - Premium features access
- ✅ **Level Up** - Bonus rewards for progression
- ✅ **Between Stages** - Natural break + incentive
- ✅ **Challenge Complete** - Celebrate with rewards

<br/>

### 📝 Implementation

#### Step 1: Initialize Rewarded Interstitial

```kotlin
class MainActivity : AppCompatActivity() {
    private lateinit var rewardedInterstitial: EasyRewardedInterstitialAd
    
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        
        // Initialize
        rewardedInterstitial = EasyRewardedInterstitialAd(
            this,
            "ca-app-pub-3940256099942544/5354046379"
        )
        
        setupListener()
        rewardedInterstitial.load()
    }
}
```

#### Step 2: Setup Listener

```kotlin
private fun setupListener() {
    rewardedInterstitial.setListener(object : EasyRewardedInterstitialListener {
        
        override fun onRewardEarned() {
            Log.d("RewardedInt", "🎉 User earned reward!")
            // Grant reward
            grantReward()
        }
        
        override fun onAdClosed() {
            Log.d("RewardedInt", "🔄 Ad closed")
            // Preload next ad
            rewardedInterstitial.load()
        }
        
        override fun onAdFailed(error: String) {
            Log.e("RewardedInt", "❌ Failed: $error")
        }
    })
}
```

#### Step 3: Show Ad

```kotlin
fun showRewardedInterstitial() {
    rewardedInterstitial.showIfAvailable()
}
```

<br/>

### 🎯 Best Practices

| ✅ Do | ❌ Don't |
|-------|----------|
| Preload ads in advance | Load when user triggers action |
| Use at natural break points | Interrupt gameplay/content |
| Clearly show reward value | Use vague messaging |
| Make rewards meaningful | Offer insignificant rewards |
| Reload immediately after close | Forget to preload next ad |

<br/>

### 📖 Official Documentation

- [Google AdMob Rewarded Interstitial Guide](https://developers.google.com/admob/android/rewarded-interstitial)
- [Rewarded Interstitial Best Practices](https://support.google.com/admob/answer/9884467)

</details>

<br/>

---

<div align="center">

# 🎯 Advanced Features

</div>

## 🔐 Pro/Ad-Free Version Support

The SDK includes built-in support for Pro/Ad-Free versions with automatic ad management.

### 🎁 How It Works

When you enable Pro features, the SDK automatically:

- ❌ **Stops loading new ads**
- 🗑️ **Destroys loaded ads**
- 👁️ **Hides banner views**
- ✅ **Works across all ad types**

<br/>

### 📝 Implementation

#### Enable Pro/Ad-Free Mode

```kotlin
// Call this when user purchases Pro version
EasyAdsConfig.enableProFeatures()
```

#### Usage in Your App

```kotlin
class MainActivity : AppCompatActivity() {
    
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        
        // Check if user has Pro version (from your billing)
        if (BillingManager.hasPurchased("pro_version")) {
            EasyAdsConfig.enableProFeatures()
        }
        
        // Load ads normally - SDK handles Pro users automatically
        loadAds()
    }
    
    private fun loadAds() {
        // Banner will NOT load if Pro is enabled
        bannerView.load(adUnitId = "YOUR_AD_UNIT_ID")
        
        // Interstitial will NOT load if Pro is enabled
        interstitial.load()
        
        // All ad types respect Pro status automatically!
    }
}
```

<br/>

### 🎯 Supported Ad Types

| Ad Type | Pro Support |
|---------|-------------|
| Banner | ✅ Auto-hide & skip loading |
| Interstitial | ✅ Skip loading |
| Rewarded | ✅ Skip loading |
| Rewarded Interstitial | ✅ Skip loading |
| Native | ✅ Auto-hide & skip loading |

<br/>

### 💡 Best Practices

| ✅ Do | ❌ Don't |
|-------|----------|
| Call `enableProFeatures()` in Application class | Check Pro status manually before each ad |
| Let SDK handle ad visibility automatically | Manually hide/show ad views |
| Enable Pro immediately after purchase | Delay enabling Pro features |
| Use single source of truth for Pro status | Check Pro status in multiple places |

<br/>

### 📋 Complete Example

```kotlin
class MyApp : Application() {
    
    override fun onCreate() {
        super.onCreate()
        
        // Initialize SDK
        EasyAdSdk.initialize(
            context = this,
            isDebug = BuildConfig.DEBUG
        )
        
        // Check and enable Pro if purchased
        checkProStatus()
    }
    
    private fun checkProStatus() {
        // Check your billing/purchase status
        val hasPro = PreferenceManager.getBoolean("has_pro", false)
        
        if (hasPro) {
            EasyAdsConfig.enableProFeatures()
            Log.d("Ads", "🎉 Pro user - Ads disabled")
        }
    }
}
```

<br/>

## 📊 Complete Listener Reference

<details>
<summary><b>🎪 View All Listener Interfaces</b></summary>

<br/>

```kotlin
// 🏷️ Banner Ad Listener
interface EasyBannerListener {
    fun onAdLoaded()
    fun onAdFailed(error: String)
    fun onAdClicked()
}

// 🎬 Interstitial Ad Listener
interface EasyInterstitialListener {
    fun onAdLoaded()
    fun onAdFailed(error: String)
    fun onAdShown()
    fun onAdClicked()
    fun onAdClosed()
}

// 🎁 Rewarded Ad Listener
interface EasyRewardedListener {
    fun onAdLoaded()
    fun onAdFailed(error: String)
    fun onAdShown()
    fun onUserEarnedReward()
    fun onAdClicked()
    fun onAdClosed()
}

// 🎨 Native Ad Listener
interface EasyNativeAdListener {
    fun onAdLoaded(nativeAd: NativeAd)
    fun onAdFailedToLoad(errorMessage: String)
    fun onAdClicked()
    fun onAdImpression()
}
```

</details>

<br/>

[//]: # (---)

[//]: # ()
[//]: # (<div align="center">)

[//]: # ()
[//]: # (# 🎨 Showcase)

[//]: # ()
[//]: # (### Real Apps Built with EasyToUse AdMob SDK)

[//]: # ()
[//]: # (</div>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (<div align="center">)

[//]: # ()
[//]: # (<table>)

[//]: # (<tr>)

[//]: # (<td align="center" width="100%">)

[//]: # ()
[//]: # (<img src="https://play-lh.googleusercontent.com/9XKD5S7rwQ6FiPXSyp9SzLXfIue88ntf9sJ9K2Iy7g6B8c7q8J3RzR5c8xjhBN5YHg=s180-rw" width="120" />)

[//]: # ()
[//]: # (### 📱 **iLoveFile - File Manager & Explorer**)

[//]: # ()
[//]: # (*Powerful file management with seamless ad integration*)

[//]: # ()
[//]: # (<p>)

[//]: # (<img src="https://img.shields.io/badge/Category-Productivity-blue?style=flat-square" />)

[//]: # (<img src="https://img.shields.io/badge/Rating-★★★★☆%204.2-yellow?style=flat-square" />)

[//]: # (<img src="https://img.shields.io/badge/Downloads-10K+-green?style=flat-square" />)

[//]: # (<img src="https://img.shields.io/badge/Powered%20by-EasyAds-blueviolet?style=flat-square" />)

[//]: # (</p>)

[//]: # ()
[//]: # (**Features:**)

[//]: # (- 📂 Advanced file browsing and management)

[//]: # (- ☁️ Cloud storage integration)

[//]: # (- 🎵 Built-in media player)

[//]: # (- 🎯 **Seamless native ad integration** using EasyAds SDK)

[//]: # (- 💰 **3x revenue increase** with optimized ad placement)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (<a href="https://play.google.com/store/apps/details?id=com.goldensuccor.ilovefile">)

[//]: # (  <img src="https://img.shields.io/badge/Download%20on-Google%20Play-3DDC84?style=for-the-badge&logo=google-play&logoColor=white" />)

[//]: # (</a>)

[//]: # ()
[//]: # (<br/>)

[//]: # (<br/>)

[//]: # ()
[//]: # (> *"EasyAds SDK transformed our monetization strategy. Native ads blend perfectly with our file list, and the Pro version support works flawlessly!"*  )

[//]: # (> **— iLoveFile Development Team**)

[//]: # ()
[//]: # (</td>)

[//]: # (</tr>)

[//]: # (</table>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (### 🚀 Want Your App Featured Here?)

[//]: # ()
[//]: # (We'd love to showcase apps built with EasyAds SDK! )

[//]: # ()
[//]: # (<a href="https://github.com/parthivz1/EasyAds/issues/new?template=showcase-submission.md">)

[//]: # (  <img src="https://img.shields.io/badge/Submit%20Your%20App-4CAF50?style=for-the-badge&logo=android&logoColor=white" />)

[//]: # (</a>)

[//]: # ()
[//]: # (</div>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (---)

<div align="center">

# 🔮 Future Roadmap

### 🚀 What's Coming to EasyAds

</div>

<br/>

<table>
<tr>
<td align="center" width="33%">

### 📘 **Facebook Ads Integration**

<img src="https://img.shields.io/badge/Status-Planned-blue?style=for-the-badge" />

<br/><br/>

Support for Facebook Audience Network ads:
- Banner Ads
- Interstitial Ads
- Rewarded Videos
- Native Ads
- Same easy-to-use API

**Expected:** Q2 2024

</td>
<td align="center" width="33%">

### 🟡 **Yandex Ads Integration**

<img src="https://img.shields.io/badge/Status-Planned-blue?style=for-the-badge" />

<br/><br/>

Yandex Mobile Ads support:
- Banner formats
- Fullscreen ads
- Rewarded ads
- Native advertising
- Seamless integration

**Expected:** Q3 2024

</td>
<td align="center" width="33%">

### 🎯 **Mediation Support**

<img src="https://img.shields.io/badge/Status-Under%20Review-yellow?style=for-the-badge" />

<br/><br/>

Multi-network mediation:
- AdMob Mediation
- Max by AppLovin
- ironSource
- Automatic optimization
- Revenue maximization

**Expected:** Q4 2024

</td>
</tr>
</table>

<br/>

[//]: # (<div align="center">)

[//]: # (### 💡 Have a feature request?)

[//]: # ()
[//]: # ([Submit your idea]&#40;https://github.com/parthivz1/EasyAds/discussions/new?category=ideas&#41; and help shape the future of this library!)

[//]: # (</div>)

[//]: # (<br/>)

[//]: # (---)

<div align="center">

# 📚 Resources

</div>

<br/>

<table>
<tr>
<td align="center" width="33%">

### 📖 **Documentation**

**Official Google AdMob Guides:**

🏷️ [Banner Ads Integration](https://developers.google.com/admob/android/banner)

🎬 [Interstitial Ads Guide](https://developers.google.com/admob/android/interstitial)

🎁 [Rewarded Ads Documentation](https://developers.google.com/admob/android/rewarded)

🎨 [Native Ads Advanced Guide](https://developers.google.com/admob/android/native/start)

📊 [AdMob Best Practices](https://support.google.com/admob/answer/6128877)

⚙️ [Test Ads Setup](https://developers.google.com/admob/android/test-ads)

</td>
<td align="center" width="33%">

### 💬 **Community**

**Get Help & Connect:**

[//]: # (<a href="https://stackoverflow.com/questions/tagged/admob"><img src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=for-the-badge&logo=stack-overflow&logoColor=white" /></a>)

[//]: # (<a href="https://github.com/parthivz1/EasyAds/discussions"><img src="https://img.shields.io/badge/GitHub%20Discussions-181717?style=for-the-badge&logo=github&logoColor=white" /></a>)

<br/>

📌 Ask questions about AdMob on Stack Overflow

💬 Join discussions about the SDK on GitHub

🗣️ Share your experiences and solutions

🤝 Help other developers

</td>
<td align="center" width="33%">

### 🐛 **Support**

**Need Help?**

[//]: # (<a href="https://github.com/parthivz1/EasyAds/issues/new?template=bug_report.md"><img src="https://img.shields.io/badge/Report%20Bug-red?style=for-the-badge&logo=github&logoColor=white" /></a>)

[//]: # (<a href="https://github.com/parthivz1/EasyAds/issues/new?template=feature_request.md"><img src="https://img.shields.io/badge/Request%20Feature-blue?style=for-the-badge&logo=github&logoColor=white" /></a>)

<br/>

🐛 Found a bug? Report it

💡 Have an idea? Request it

📧 Need help? Open an issue

⭐ Like it? Star the repo

</td>
</tr>
</table>

<br/>

[//]: # (---)

[//]: # ()
[//]: # (<div align="center">)

[//]: # ()
[//]: # (# 🤝 Contributing)

[//]: # ()
[//]: # (</div>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (<div align="center">)

[//]: # ()
[//]: # (### 🚧 Contributions Currently Not Available)

[//]: # ()
[//]: # (We're currently setting up our contribution guidelines and reviewing process. )

[//]: # ()
[//]: # (**Coming Soon:**)

[//]: # (- ✅ Contribution guidelines)

[//]: # (- ✅ Code of conduct)

[//]: # (- ✅ Development setup guide)

[//]: # (- ✅ Pull request template)

[//]: # (- ✅ Issue templates)

[//]: # ()
[//]: # (**Want to contribute when we open up?**)

[//]: # ()
[//]: # (⭐ Star this repo to stay updated  )

[//]: # (👀 Watch for announcements  )

[//]: # (💬 Join [GitHub Discussions]&#40;https://github.com/parthivz1/EasyAds/discussions&#41;)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (<img src="https://img.shields.io/badge/Contributions-Coming%20Soon-yellow?style=for-the-badge" />)

[//]: # ()
[//]: # (</div>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (---)

<div align="center">

# 📄 License

</div>

<br/>

```
Apache License 2.0

Copyright (c) 2024 [Your Name]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[//]: # (<div align="center">)

[//]: # (**TL;DR:** You can freely use, modify, and distribute this library. See [LICENSE]&#40;LICENSE&#41; for full details.)

[//]: # (</div>)

<br/>

---

<div align="center">

[//]: # ()
[//]: # (# 📞 Contact & Support)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (<p>)

[//]: # (<a href="mailto:support@easyads.dev"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>)

[//]: # (<a href="https://github.com/parthivz1/EasyAds/discussions"><img src="https://img.shields.io/badge/Discussions-181717?style=for-the-badge&logo=github&logoColor=white" /></a>)

[//]: # (<a href="https://twitter.com/EasyAdsSDK"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>)

[//]: # (<a href="https://linkedin.com/company/easyads"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>)

[//]: # (</p>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (### ⭐ If EasyAds helped you, please star this repository!)

[//]: # ()
[//]: # (### 💬 Join Our Community)

[//]: # ()
[//]: # (<a href="https://github.com/parthivz1/EasyAds/discussions">)

[//]: # (  <img src="https://img.shields.io/badge/Join%20Discussions-4CAF50?style=for-the-badge&logo=github&logoColor=white" />)

[//]: # (</a>)

[//]: # ()
[//]: # (<br/>)

[//]: # (<br/>)

[//]: # ()
[//]: # (### 💖 Support This Project)

[//]: # ()
[//]: # (<a href="https://www.buymeacoffee.com/easyads"><img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" /></a>)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (---)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (**Made with ❤️ for the Android Developer Community**)

[//]: # ()
[//]: # (*Empowering developers to monetize better, one app at a time.*)

[//]: # ()
[//]: # (<br/>)

[//]: # ()
[//]: # (<p>)

[//]: # (  <img src="https://img.shields.io/github/stars/parthivz1/EasyAds?style=social" />)

[//]: # (  <img src="https://img.shields.io/github/forks/parthivz1/EasyAds?style=social" />)

[//]: # (  <img src="https://img.shields.io/github/watchers/parthivz1/EasyAds?style=social" />)

[//]: # (</p>)

[//]: # ()
[//]: # (<br/>)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" />

</div>
