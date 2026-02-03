# Image Gathering Quick Checklist

Use this checklist if you want to add real screenshots/photos to the presentation (optional - presentation works fine with placeholders).

**Time Required:** 2-3 hours total

---

## Priority 1: Must-Have (30 minutes)

### ✅ Your Headshot
- [ ] Find existing professional photo OR
- [ ] Take new photo with phone (good lighting, neutral background)
- [ ] Crop to square (250x250px minimum)
- [ ] Save as: `headshot.jpg`

### ✅ Discord Screenshot
- [ ] Open your Nations615 Discord server
- [ ] Ensure 100+ member count is visible
- [ ] Screenshot the server overview
- [ ] Save as: `discord-server.png`

---

## Priority 2: Core Content (1-1.5 hours)

### ✅ Social Media Scheduler Screenshot
- [ ] Go to buffer.com or hootsuite.com
- [ ] Sign up for free trial (email required)
- [ ] Navigate to post scheduling interface
- [ ] Screenshot the calendar/queue view showing Instagram/Facebook
- [ ] Save as: `social-scheduler.png`

### ✅ Email Newsletter Screenshot
- [ ] Go to mailchimp.com or beehiiv.com
- [ ] Sign up for free trial (email required)
- [ ] Open newsletter/email builder
- [ ] Screenshot the template editor interface
- [ ] Save as: `newsletter-builder.png`

### ✅ Nations Photos
- [ ] Go to instagram.com/thenations615
- [ ] Find 3-4 good community photos:
  - Neighborhood street scene
  - Community event (Firefly 5K, cleanup, etc.)
  - Fat Bottom Brewery (if available)
  - Local business or gathering
- [ ] Download/screenshot images
- [ ] Save as: `nations-photo-1.jpg`, `nations-photo-2.jpg`, etc.

---

## Priority 3: Nice-to-Have (30 minutes)

### ✅ AI Caption Example
- [ ] Go to chat.openai.com (or similar AI tool)
- [ ] Ask: "Create engaging Instagram caption for Nations Neighborhood Association monthly meeting at Fat Bottom Brewery"
- [ ] Screenshot the generated caption
- [ ] Save as: `ai-caption.png`

### ✅ Discord Bot Examples (if you have a bot)
- [ ] Trigger bot welcome message OR create mockup
- [ ] Screenshot the message
- [ ] Save as: `discord-bot-welcome.png`
- [ ] Screenshot bot event reminder (or mockup)
- [ ] Save as: `discord-bot-reminder.png`

---

## Quick Screenshot Tips

**Mac:**
- Cmd+Shift+4, then spacebar = screenshot window
- Cmd+Shift+3 = screenshot entire screen
- Screenshots save to Desktop

**Windows:**
- Windows+Shift+S = screenshot tool
- Snipping Tool app = more control

**Good Screenshots:**
- Clean interface (close unnecessary windows)
- Readable text (don't zoom out too much)
- 1200x900px minimum
- PNG format preferred (better quality)

---

## Adding Images to Presentation

Once you have your images:

1. **Save all images** in the same folder as `presentation.html`

2. **Edit presentation.html** in a text editor (TextEdit, VS Code, etc.)

3. **Find placeholder divs** and replace with images:

```html
<!-- Example: Replace headshot placeholder -->
<div class="headshot">
    <img src="headshot.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>

<!-- Example: Replace social media screenshot -->
<div class="placeholder">...</div>
<!-- Replace entire div with: -->
<img src="social-scheduler.png" style="width: 100%; height: 100%; object-fit: contain;">
```

4. **Save and refresh** browser to see changes

---

## Or: Skip Images Entirely

**The presentation works GREAT without images!**

During your talk:
- Describe what the screenshot would show
- Focus on your spoken content (most important)
- Audience understands the concept without seeing exact screenshots

**Your credibility (100+ Discord members, 2 years) is more powerful than any screenshot.**

---

## Realistic Timeline

**Option A: Add just headshot + Discord screenshot (30 min)**
- Most important visuals
- Shows you're the real deal (your actual Discord)
- Presentation feels personal

**Option B: Add all screenshots (2-3 hours)**
- Sign up for tool free trials
- Take all screenshots
- Gather Nations photos
- Edit HTML to add images
- Most polished result

**Option C: Use placeholders (0 min)**
- Present as-is
- Focus on delivery and content
- Still professional and effective

Choose based on how much time you have before the NNA meeting!
