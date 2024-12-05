# Tax Credit PDF Generator

React-based PDF generator for tax credit documentation with Next.js and Tailwind CSS.

## Setup

```bash
# Create new Next.js project
npx create-next-app@latest tax-credit-viewer --typescript --tailwind --app

# Install dependencies
cd tax-credit-viewer
npm install react-to-print@2.14.13 --legacy-peer-deps
```

## Project Structure

```
tax-credit-viewer/
├── app/
│   ├── globals.css
│   └── page.tsx
├── components/
│   ├── TaxCreditPDF.tsx
│   └── TaxCreditTemplate.tsx
└── package.json
```

## Development

```bash
npm run dev
```

Visit http://localhost:3000

## Features

- 5-page tax credit documentation
- Custom SVG logos
- Responsive tables
- Print-optimized layout
- A4 page sizing
- Professional formatting

## Print Settings

For optimal PDF generation:
- Paper size: A4
- Margins: Default
- Background graphics: Enabled

## Technologies

- Next.js 14
- React 19
- Tailwind CSS
- react-to-print