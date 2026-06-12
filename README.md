<h1 align="center">Aarav Gupta</h1>
<table width="100%">
<tr><td width="100%">

<pre><code><span style="color:#FF7B72">import</span> <span style="color:#D2A8FF">Foundation</span>

<span style="color:#FF7B72">struct</span> <span style="color:#D2A8FF">AaravGupta</span>: <span style="color:#D2A8FF">Person</span>, <span style="color:#D2A8FF">iOSDeveloper</span>, <span style="color:#D2A8FF">SecurityResearcher</span> {
    <span style="color:#8B949E">// personal details</span>
    <span style="color:#FF7B72">var</span> age = <span style="color:#79C0FF">19</span>
    <span style="color:#FF7B72">let</span> email = <span style="color:#A5D6FF">"atpugvaraa@gmail.com"</span>
    <span style="color:#FF7B72">let</span> socialHandle = <span style="color:#A5D6FF">"@atpugvaraa"</span>
    <!-- <span style="color:#FF7B72">let</span> alias = <span style="color:#A5D6FF">"atpugvaraa"</span> -->
    <span style="color:#8B949E">// this matters i guess</span>
    <span style="color:#FF7B72">var</span> progLangs = [<span style="color:#A5D6FF">"Swift"</span>, <span style="color:#A5D6FF">"Obj-C"</span>, <span style="color:#A5D6FF">"TS"</span>, <span style="color:#A5D6FF">"Go"</span>, <span style="color:#A5D6FF">"C#"</span>, <span style="color:#A5D6FF">"Java/Kotlin"</span>, <span style="color:#A5D6FF">"Rust"</span>, <span style="color:#A5D6FF">"Zig"</span>, <span style="color:#A5D6FF">"..."</span>]

    <span style="color:#FF7B72">var</span> workingOn: [<span style="color:#D2A8FF">projectName</span>: <span style="color:#D2A8FF">String</span>] = [
        <span style="color:#8B949E">// iOS</span>
        <a href="https://cisum.studio">cisum</a>: <span style="color:#A5D6FF">"music streaming — YouTube/Spotify/iTunes/Tidal reverse-engineered internal APIs"</span>,
        <a href="https://github.com/atpugvaraa/Bookmarkd">Bookmarkd</a>: <span style="color:#A5D6FF">"answers the question — where to find and read books (even for free)"</span>,
        Venn: <span style="color:#A5D6FF">"organize your tasks using venn diagrams"</span>,
        <a href="https://github.com/atpugvaraa/paperwait">paperwait</a>: <span style="color:#A5D6FF">"use your iDevices as a drawing tablet"</span>,
        addictshun: <span style="color:#A5D6FF">"stop doom-scrolling gang"</span>,
        Project Arise: <span style="color:#A5D6FF">"solo-leveling themed gamified habit/fitness app"</span>,
        <a href="https://github.com/atpugvaraa/ringo">ringo</a>: <span style="color:#A5D6FF">"your actual personal assistant"</span>,

        <span style="color:#8B949E">// Work</span>
        HealthPod: <span style="color:#A5D6FF">"from scratch to App Store for my internship"</span>,
        Helix 26': <span style="color:#A5D6FF">"react-native app for my annual college tech fest"</span>,
        Saturnalia 26': <span style="color:#A5D6FF">"app for my college's flagship techno-cultural fest"</span>,

        <span style="color:#8B949E">// macOS & cli</span>
        <a href="https://github.com/atpugvaraa/quickly">quickly</a>: <span style="color:#A5D6FF">"a package manager for multi-platform Swift"</span>,
        <a href="https://github.com/atpugvaraa/DheetCode">DheetCode</a>: <span style="color:#A5D6FF">"a stubborn screen timeout until you solve a LeetCode"</span>,

        <span style="color:#8B949E">// weird SwiftUI obsession</span>
        <a href="https://github.com/atpugvaraa/swift.js">swift.js</a>: <span style="color:#A5D6FF">"use SwiftUI on Web — transpiles SwiftUI to Next.js"</span>,
        <a href="https://github.com/atpugvaraa/QuickUI">QuickUI</a>: <span style="color:#A5D6FF">"SwiftUI for multi-platform using Raylib"</span>,

        <span style="color:#8B949E">// iOS security research</span>
        <a href="https://github.com/atpugvaraa/heavykatana">heavykatana</a>: <span style="color:#A5D6FF">"understanding the DarkSword WebKit JS-chain by @zeroxjf"</span>,
        <a href="https://github.com/atpugvaraa/shinobu">shinobu</a>: <span style="color:#A5D6FF">"iOS 26.1 PoC on my iPhone 14 — by @GenericCoding & @zeroxjf"</span>,
        <a href="https://github.com/atpugvaraa/cortisol">cortisol</a>: <span style="color:#A5D6FF">"my Lara fork to play with DarkSword on iOS 18.6"</span>,

        <span style="color:#8B949E">// packages</span>
        <a href="https://github.com/atpugvaraa/YouTubeSDK">YouTubeSDK</a>: <span style="color:#A5D6FF">"Swift SDK for YouTube's private InnerTube API"</span>,
        <a href="https://github.com/atpugvaraa/NodeJS.swift">NodeJS.swift</a>: <span style="color:#A5D6FF">"run a node server on iPhone via nodejs-mobile"</span>,
        <a href="https://github.com/atpugvaraa/Aesthetics">Aesthetics</a>: <span style="color:#A5D6FF">"UI components I made and use in my apps"</span>,
        <a href="https://github.com/atpugvaraa/AppRouter">AppRouter</a>: <span style="color:#A5D6FF">"the best possible navigation router with a good-ish API"</span>,

        <span style="color:#8B949E">// TypeScript</span>
        <a href="https://iks.thapar.edu">Thapar-IKS</a>: <span style="color:#A5D6FF">"site for my uni's Indian Knowledge System Center"</span>,

        <span style="color:#8B949E">// Rust</span>
        <a href="https://github.com/atpugvaraa/oxytocin">oxytocin</a>: <span style="color:#A5D6FF">"a love bomb for the jailbreak community from me &lt;3"</span>,
    ]

    <span style="color:#FF7B72">var</span> contributions = [<a href="https://github.com/the-ora/browser">Ora Browser</a>, <span style="color:#A5D6FF">"..."</span>]
    <span style="color:#FF7B72">var</span> langs = [<span style="color:#A5D6FF">"Hindi"</span>, <span style="color:#A5D6FF">"English"</span>, <span style="color:#A5D6FF">"German (elementary)"</span>, <span style="color:#A5D6FF">"French, Russian, Japanese (wannabe)"</span>]
}
</code></pre>

</td></tr>
</table>

<h3 align="center">Contact me</h3>
<p align="center">
  <a href="https://x.com/atpugvaraa" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="atpugvaraa" height="30" width="40" /></a>
  <a href="https://discord.gg/852755623501758515" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="discord" height="30" width="40" /></a>
</p>

<!---
atpugvaraa/atpugvaraa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
