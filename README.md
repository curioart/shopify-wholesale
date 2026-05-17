# Shopify Wholesale Greeting Card Theme

A minimal Shopify theme for selling greeting cards at wholesale prices.

## 🚀 Quick Start

### Prerequisites
- [Shopify CLI](https://shopify.dev/docs/api/shopify-cli)
- Node.js 14+

### Setup
```bash
# Clone this repository
git clone https://github.com/curioart/shopify-wholesale.git
cd shopify-wholesale

# Install dependencies (if needed)
npm install

# Start development server
shopify theme dev
```

This will launch a preview of your theme at `http://localhost:9292`

## 📁 Project Structure

```
.
├── config/
│   ├── settings_schema.json    # Theme customization settings
│   └── locales/en.json         # Translations
├── layout/
│   └── theme.liquid            # Main HTML layout
├── sections/
│   ├── hero.liquid             # Hero banner section
│   └── featured_products.liquid # Product grid section
├── snippets/
│   └── product-card.liquid     # Reusable product card component
├── templates/
│   └── index.json              # Homepage configuration
└── README.md
```

## 🎨 Customization

### Theme Settings
Visit `/admin/themes/current/editor` in your Shopify dashboard to customize:
- Colors (background, text, accent, buttons)
- Page width and margins
- Fonts
- Wholesale settings (minimum order, inquiry email)

### Adding Products
1. Create products in Shopify Admin
2. Add them to the "featured" collection to display on homepage
3. Configure prices per product

## 📝 Key Features

✅ Responsive design (mobile, tablet, desktop)  
✅ Customizable color scheme  
✅ Wholesale-focused layout  
✅ Featured products section  
✅ Hero banner  
✅ Clean, modular code structure  

## 🔄 Next Steps

1. **Add Your Products** - Create greeting card products in Shopify Admin
2. **Customize Branding** - Adjust colors, fonts, hero image
3. **Set Wholesale Pricing** - Configure tiered pricing for bulk orders
4. **Add Collections** - Organize by occasion (Birthday, Wedding, etc.)
5. **Create Policies** - Add wholesale terms, shipping, returns

## 📚 Resources

- [Shopify Theme Development](https://shopify.dev/docs/storefronts/themes)
- [Liquid Template Language](https://shopify.dev/docs/api/liquid)
- [Shopify CLI Documentation](https://shopify.dev/docs/api/shopify-cli)

## 📧 Support

For wholesale inquiries, update `business_inquiry_email` in theme settings.

---

Built with ❤️ for CurioArt Wholesale
