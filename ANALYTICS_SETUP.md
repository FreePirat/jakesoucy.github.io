# Analytics Setup for GitHub Pages

## Google Analytics Setup

1. **Create a Google Analytics Account**
   - Go to [Google Analytics](https://analytics.google.com/)
   - Sign in with your Google account
   - Create a new property for your website

2. **Get Your Measurement ID**
   - In Google Analytics, go to Admin > Property > Data Streams
   - Select your web stream
   - Copy your Measurement ID (format: G-XXXXXXXXXX)

3. **Update Your Website**
   - Open `index.html`
   - Find line 9: `gtag('config', 'G-XXXXXXXXXX');`
   - Replace `G-XXXXXXXXXX` with your actual Measurement ID
   - Also update line 8 with the same ID in the script src

4. **Deploy Changes**
   - Commit and push your changes to GitHub
   - GitHub Pages will automatically deploy your updated site

## What Analytics Tracks

Your portfolio now tracks:
- **Page Views**: How many people visit your site
- **Section Views**: Which sections users spend time reading
- **Language Changes**: When users switch between English/French
- **Form Submissions**: Contact form usage
- **External Link Clicks**: Clicks to GitHub, LinkedIn, etc.
- **Resume Downloads**: When someone downloads your PDF
- **Navigation Clicks**: Which sections users navigate to
- **Performance**: Page load times

## Privacy Considerations

- Analytics data is anonymous and aggregated
- No personal information is collected
- Users can opt-out using browser settings
- Consider adding a privacy policy if your site grows

## Alternative Analytics (Free for GitHub Pages)

If you prefer not to use Google Analytics, consider:
- **GitHub Insights**: Built-in traffic analytics for GitHub repositories
- **Plausible**: Privacy-focused, lightweight analytics
- **Simple Analytics**: GDPR compliant, simple interface

## Viewing Your Data

1. Go to [Google Analytics](https://analytics.google.com/)
2. Select your property
3. View reports in the left sidebar:
   - **Reports > Engagement > Events** - See custom events
   - **Reports > Engagement > Pages** - See page views
   - **Reports > Tech > User-Agent** - See visitor technology

Allow 24-48 hours for data to start appearing in your reports.