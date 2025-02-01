# ShayHub Translator - Update v1.0.4

## 🚀 New Main Features

### Multi-Key System
- **New Multi-Key Management System** for increased translation volume
- Easy management of multiple API keys through the new administration
- Automatic combination of volumes from all active keys
- Intelligent load distribution between keys
- Automatic failover when key limit is exhausted

### Live Preview System
- **New Live Preview** during translation
- Two-column display (Original / Translation)
- Real-time display of translations
- Pause/Resume function for preview
- Maintains exact formatting

### Improved Translation Logic
- Optimized handling of special characters and formatting
- Intelligent detection of text parts to be translated
- Improved handling of tab-separated files
- Correct translation of all text components while maintaining IDs

### New locale_string.txt Support
- **Intelligent ID detection** through uppercase and underscore analysis
- Perfect format retention:
  - Quotation marks and semicolons are preserved
  - Line structure is exactly maintained
- Secure protection of formatting characters:
  - All %d, %s placeholders remain unchanged
  - Correct positioning after translation
- Improved error handling for invalid lines

## 📊 Improved Monitoring

### API Usage
- Real-time display of combined API usage
- Progress bar with color coding (Blue/Orange/Red)
- Display of active keys and total volume
- Automatic warnings at high utilization (>90%)

### Translation Progress
- Detailed progress bar during translation
- Display of current line and overall progress
- Status updates per language for multiple translations

## 🛠️ Additional Improvements

### Bug Report
- New Bug Report Button
- Direct reporting to server admin
- Cooldown system (1 report per hour)
- Automatic system version detection

### Technical Optimizations
- Improved character encoding (UTF-8 support)
- Optimized file processing
- Increased stability for large translations
- Improved error handling during translation

---
*Developed by Shay*
