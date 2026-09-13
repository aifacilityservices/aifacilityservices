# AI Facility Services Website

Professional website for AI Facility Services - Commercial and Residential Cleaning, Facility & Property Maintenance.

## Features

- ✨ Sophisticated modern design with responsive layout
- 📱 Mobile-friendly interface
- 🎨 Professional branding with black, grey, and green colors
- 📋 Service showcase for commercial and residential offerings
- 📞 Easy contact and quote request system
- ⚡ Fast loading and smooth animations
- 🔍 SEO-friendly structure

## Services Offered

### Commercial Services
- Janitorial Services
- Facility Maintenance
- Pressure Washing
- Line Painting

### Residential Services
- Residential Cleaning
- Lawn & Grounds Maintenance
- Snow Removal
- Property Maintenance

## Service Areas

We serve the GTA and surrounding areas including:
- Toronto
- Mississauga
- Brampton
- Oakville
- Burlington
- Hamilton
- York Region
- Durham Region
- And surrounding areas

## Contact Information

- **Phone**: (416) 838-0333
- **Email**: Info@aifacilityservices.ca
- **Service Area**: GTA and Surrounding Areas

## How to Host on GitHub Pages

1. Go to repository settings
2. Scroll to "GitHub Pages" section
3. Select "main" branch as source
4. Your site will be available at: `https://aifacilityservices.github.io/aifacilityservices`

## How to Customize

1. **Edit Business Information**:
   - Open `index.html`
   - Update phone number, email, and service areas as needed

2. **Change Colors**:
   - Open `styles.css` or `css/style.css`
   - Modify the color variables at the top:
     - `--bg-primary`: Main dark background color
     - `--bg-secondary`: Section background color
     - `--accent`: Primary green action color

3. **Add Your Photos**:
   - Replace image URLs in `index.html` with your own photos
   - Current images are from Unsplash (placeholder images)

4. **Update Services**:
   - Add or remove service cards in the Services section

5. **Configure Contact Form Endpoint**:
   - The contact page can use a deployment-provided endpoint via `window.CONTACT_FORM_ENDPOINT`
   - Load that global before the inline script at the end of `contact.html` executes (for example in the `<head>` or immediately above the inline script)
   - Define it in a global script, for example:
     - `window.CONTACT_FORM_ENDPOINT = "https://formspree.io/f/your_form_id";`
   - Endpoint validation allows only same-origin `/api/contact`, Formspree `/f/<id>` URLs, and FormSubmit single-path endpoints
   - When configured, the page script automatically switches the form to `POST` using standard browser form encoding
   - Hidden fields `_honey` and `_subject` in `contact.html` are intended for Formspree/FormSubmit-compatible endpoints
   - If not configured, the page hides the form and shows direct contact instructions (phone/email)

## 15+ Years of Excellence

AI Facility Services has been serving the Greater Toronto Area for over 15 years with professional, reliable facility and property maintenance services.

---

**Last Updated**: 2026
**Website**: aifacilityservices.ca