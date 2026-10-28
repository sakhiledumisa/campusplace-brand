# CampusPlace Brand Assets Structure

Official CampusPlace brand assets organized for easy access.

## Directory Structure

### `/logo/` - Brand Logos & Icons
All logo files in various formats and sizes for web, mobile, and PWA usage.

**Main Logos:**
- `logo-512.svg` - Primary logo (SVG, scalable)
- `logo-512.png` - Primary logo (PNG, 512×512px)
- `logo-192.png` - Primary logo (PNG, 192×192px)

**Favicons:**
- `favicon.ico` - Multi-resolution ICO (16, 32, 48px)
- `favicon-16x16.png` - 16×16px PNG
- `favicon-32x32.png` - 32×32px PNG

**Mobile/App Icons:**
- `apple-touch-icon.png` - 180×180px (iOS Safari)
- `android-chrome-192x192.png` - 192×192px (Android, PWA)
- `android-chrome-512x512.png` - 512×512px (Android, PWA)

### `/bimi/` - Email Authentication
BIMI-compliant logo for email authentication (Brand Indicators for Message Identification).

- `bimi.svg` - SVG Tiny PS format, 512×512px, <32KB

### `/og/` - Social Media
Reserved for Open Graph images, Twitter cards, and social media assets.

*Currently empty*

---

## Naming Convention

Files use descriptive names with size indicators:
```
{name}-{size}.{ext}
```

Examples:
- `logo-512.svg` - Logo at 512px
- `favicon-32x32.png` - Favicon at 32×32px
- `android-chrome-192x192.png` - Android icon at 192×192px

---

## Brand Color

**Primary:** Orange (#FF5722)

---

## Usage Guidelines

1. **Website favicon:** Use `favicon.ico` or `favicon-16x16.png`
2. **Primary branding:** Use `logo-512.svg` (scalable) or `logo-512.png`
3. **Mobile icons:** Use `apple-touch-icon.png` for iOS, `android-chrome-512x512.png` for Android
4. **PWA manifest:** Include both android-chrome sizes (192 & 512)
5. **Email authentication:** Use `bimi/bimi.svg` for BIMI setup

---

## File Inventory

**Total files: 9 logo files + 1 BIMI**

✅ Complete coverage for:
- Web favicons
- Mobile/PWA apps
- Primary branding
- Email authentication

---

**Last Updated:** October 28, 2026
