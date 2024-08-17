---
title: " "
---
Hey, I'm Jonny. I'm an Irish entrepreneur on a mission to reshape the future and enjoy life along the way. Welcome to my digital realm.

### Now
{{< rawhtml >}}<a href="https://www.cleftnotes.com/" class="accent">Launching Cleft</a>{{< /rawhtml >}} on the App Store in September 🚀

### So Far This Year
Authored the {{< rawhtml >}}<a href="https://www.skillnetireland.ie/insights/irish-immersive-technology-strategy-for-growth">Irish Immersive Tech Strategy</a>{{< /rawhtml >}}, commissioned by Eirmersive and Skillnet Ireland - Ireland can be the Wakanda of VR 🇮🇪 
   
### Featured in
[The Verge](https://www.theverge.com/24150467/delta-emulator-apple-app-voice-notes-ai-vergecast), [Forbes](https://www.forbes.com/sites/charliefink/2017/11/20/the-trillion-dollar-3d-telepresence-gold-mine/), [Gartner](https://www.gartner.com/en/articles/what-s-new-in-the-2023-gartner-hype-cycle-for-emerging-technologies), [The Sunday Times](https://www.thetimes.com/world/ireland-world/article/how-to-work-more-closely-in-a-remote-world-during-the-covid-19-outbreak-dkb0fbsqj), [Silicon Republic](https://www.siliconrepublic.com/start-ups/meetingroom-video-conferences-productivity-vr)

{{< rawhtml >}}
<style>
:root {
    --primary-light: #3498db;
    --primary-dark: #2980b9;
    --bg-light: #f5f8fa;
    --bg-dark: #1a202c;
    --text-light: #2c3e50;
    --text-dark: #e2e8f0;
    --accent-light: #e74c3c;
    --accent-dark: #c0392b;
    --threads-twitter-light: #000000;
    --threads-twitter-dark: #ffffff;
}

body {
    background-color: var(--bg-light);
    color: var(--text-light);
}

body.dark {
    background-color: var(--bg-dark);
    color: var(--text-dark);
}

#followButton {
    background-color: var(--primary-light);
    color: white;
}

body.dark #followButton {
    background-color: var(--primary-dark);
}

a {
    color: var(--primary-light);
}

body.dark a {
    color: var(--primary-dark);
}

.accent {
    color: var(--accent-light);
}

body.dark .accent {
    color: var(--accent-dark);
}

.threads-twitter {
    color: var(--threads-twitter-light);
}

body.dark .threads-twitter {
    color: var(--threads-twitter-dark);
}
</style>
<div style="text-align: center; margin-top: 30px;">
    <button id="followButton" style="padding: 10px 20px; background-color: var(--primary-light); color: white; border: none; border-radius: 5px; cursor: pointer; font-size: 16px;">Follow Me</button>
    
    <div id="socialLinks" style="display: none; margin-top: 15px;">
        <a href="https://www.linkedin.com/in/jonnycosgrove/" target="_blank" rel="noopener noreferrer" style="margin: 0 10px;">LinkedIn</a>
        <a href="https://www.threads.net/@jonnycosgrove_irl" target="_blank" rel="noopener noreferrer" style="margin: 0 10px;" class="threads-twitter">Threads</a>
        <a href="https://x.com/JonnyCosgrove" target="_blank" rel="noopener noreferrer" style="margin: 0 10px;" class="threads-twitter">Twitter/X</a>
        <a href="https://www.instagram.com/jonnycosgrove_irl/" target="_blank" rel="noopener noreferrer" style="margin: 0 10px;">Instagram</a>
    </div>
</div>
<script>
document.addEventListener('DOMContentLoaded', function() {
    const followButton = document.getElementById('followButton');
    const socialLinks = document.getElementById('socialLinks');

    followButton.addEventListener('click', function() {
        if (socialLinks.style.display === 'none') {
            socialLinks.style.display = 'block';
            followButton.textContent = 'Hide Links';
        } else {
            socialLinks.style.display = 'none';
            followButton.textContent = 'Follow Me';
        }
    });

    // Initialize button state
    if (socialLinks.style.display === 'none') {
        followButton.textContent = 'Follow Me';
    } else {
        followButton.textContent = 'Hide Links';
    }
});
</script>
{{< /rawhtml >}}