# Perplexity Strength Training Tracker

8-week progressive strength training program with dynamic workout generation via Perplexity Labs.

## 🚀 Live Site

Visit: **https://lagunex.github.io/PerplexityStrengthTraining/**

## 📖 Workflow: Week 1 → Week 2

### Step 1: Complete Week 1
- Open https://yourusername.github.io/perplexitystrengthtraining/
- Track all 5 days (Mon-Fri)
- Log reps, mood (😔-🔥), and completion status
- Sync data locally in your browser

### Step 2: Export Week 1 Results
- Tap **Settings** tab
- Click **"📊 Export Week Results (For Perplexity)"**
- Downloads: `week1-results-YYYY-MM-DD.json`

### Step 3: Generate Week 2 (Perplexity Labs)
- Open ChatGPT or Perplexity Labs
- Upload your `week1-results-*.json` file
- Paste this prompt:

```
I’ve completed Week 1 of my 8-week strength program.
Here’s my results JSON with completion data and mood.

Based on my actual performance (days completed, reps achieved, mood),
generate Week 2 with progressive exercise increments and variations.

My training goals after 8 weeks:
- 100 pushups per strength training session
- 150 squats per strength training session
- 50 dumbbell rows per arm with 10kg per strength training session
- swim 1km per session
- run 5kg in 30 minutes 

My training constraints:
- dumbbells of 10kg each with gradual weights
- kettebell of 12kg
- skipping rope
- 30 min per session max
- swimming twice a week
- running once a week
- no training on weekend
- full body strength training sessions

I want each week to show progressive overload toward my goal based on the previous week.

Return ONLY the week2.json file content (not wrapped in code block,
just the raw JSON object for days: monday, tuesday, wednesday, thursday, friday).

Format exactly like week1.json structure.
```

### Step 4: Upload Week 2 JSON to GitHub
- Perplexity returns: `week2.json` content
- Go to your repo: github.com/yourusername/perplexitystrengthtraining
- Click **workouts/** folder
- Click **Add file** → **Create new file**
- Name: `week2.json`
- Paste Perplexity's JSON
- **Commit changes**
- Wait 30 seconds, then refresh the website
- **Week 2 loads automatically!** 🎉

### Step 5: Track Week 2
- Repeat Steps 1-4 for each week

---

## 🎯 App Features

✅ **Week View** - See all 5 days at a glance  
✅ **Day Details** - Exercise lists with YouTube video links  
✅ **Rest Timer** - 30-second integrated timer per exercise  
✅ **Progress Tracking** - Log completed reps per exercise  
✅ **Mood Emoji** - Rate how you felt (😔-🔥)  
✅ **Completion Status** - Mark workout completed or failed  
✅ **History** - View past weeks and completion rates  
✅ **Smart Export** - Export week results optimized for Perplexity analysis  
✅ **Mobile-Optimized** - Works on iPhone, iPad, Android  
✅ **Offline Sync** - All data saved locally, no login needed  

---

## 🔄 Adding Future Weeks

Each week follows the same pattern:

1. **Complete current week** on the app
2. **Export results** (Settings → Export Week Results)
3. **Share JSON + prompt with Perplexity Labs**
4. **Receive weekN.json** from Perplexity
5. **Upload to GitHub** (workouts/weekN.json)
6. **Refresh website** - new week appears automatically

---

## 📱 Backup & Share

Your exported result files accumulate in `/results/`:

- **Keep them** for history and analysis
- **Share with Perplexity** to improve Week N+1 generation
- **Download from GitHub** anytime (raw content)

---

## ⚠️ Troubleshooting

**"Workout Files Not Found" error?**
- Ensure `workouts/week1.json` exists in your repo
- Check file is named exactly `week1.json` (case-sensitive)
- Refresh browser after uploading

**Website not updating after upload?**
- Wait 1-2 minutes for GitHub Pages to rebuild
- Hard refresh: Safari → Hold refresh icon → Hard Refresh
- Or: `Cmd+Shift+R` (Chrome/Firefox)

**Export button not working?**
- Use Safari on iPhone (best compatibility)
- Check browser console (F12) for errors

---

## 📝 First Week Upload

If starting fresh, Perplexity or I can provide `week1.json` based on your initial 8-week plan. Upload it to `workouts/week1.json` to get started.

---

**Questions?** Reference this README or share your results JSON with Perplexity Labs for next-week generation.

Happy training! 💪
