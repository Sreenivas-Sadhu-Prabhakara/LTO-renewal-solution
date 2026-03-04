# LTO Renewal Solution

A modern, Tesla-dark-themed single-page application (SPA) for managing the LTO (Land Transport Office) vehicle renewal process.

## Features

- **Modern Tesla-Dark Theme**: Sleek, contemporary design inspired by Tesla's interface
- **Phase-Based Workflow**: 5 distinct phases with visual progress tracking
- **Single-Page Application**: Smooth scrolling between all phases without page reloads
- **Sticky Navigation**: Quick access to phases with scroll-spy highlighting
- **Progress Bar**: Real-time progress indication as you scroll through phases
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Visual Diagrams**: SVG-based flowcharts and process diagrams

## Phases

1. **Pre-Renewal Phase**: Preparation and document gathering
2. **Initial Processing**: Eligibility checks and document verification
3. **Assessment Phase**: Inspection and evaluation
4. **Final Approval**: Review and authorization
5. **Issuance & Delivery**: Certificate generation and handover

## File Structure

- `index.html` - Main multi-phase workflow implementation
- `lto-spa.html` - Single-page application with all phases visible on scroll
- `LTO.css` - Styling and theming
- `LTO Workshop.xlsx` - Process documentation
- `lto_renewal_sequence.mermaid` - Sequence diagram definition
- `sequenceDiagram.mmd` - Additional sequence diagram

## Getting Started

### View Online

The project is deployed as a GitHub Page. Visit:
- **SPA Version**: https://sreenivas-sadhu-prabhakara.github.io/LTO-renewal-solution/lto-spa.html
- **Main Version**: https://sreenivas-sadhu-prabhakara.github.io/LTO-renewal-solution/

### Local Development

1. Clone the repository:
   ```bash
   git clone git@github.com:Sreenivas-Sadhu-Prabhakara/LTO-renewal-solution.git
   cd LTO-renewal-solution
   ```

2. Open in your browser:
   - Open `index.html` or `lto-spa.html` directly in a web browser
   - No build process or dependencies required

## SPA Features (lto-spa.html)

- All phases rendered on a single scrollable page
- Sticky navigation bar with phase indicators
- Scroll-spy highlighting of current phase
- Animated progress bar showing completion status
- Phase connectors and visual flow indicators

## Design Elements

- **Color Palette**: Dark theme with phase-specific accent colors
- **Typography**: Modern, clean fonts optimized for readability
- **Animations**: Smooth transitions and hover effects
- **Icons**: SVG-based icons for visual clarity

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with flexbox and grid
- **Vanilla JavaScript**: No framework dependencies
- **SVG**: Vector graphics for diagrams

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## Customization

The design and colors can be customized by modifying `LTO.css`. Key color variables:

- **Dark Background**: `#0a0e27`
- **Phase Colors**: Red, Orange, Yellow, Green, Blue
- **Text Colors**: White, Light Gray, Dark Gray

## Author

**Sreenivas Sadhu Prabhakara**

For questions or improvements, please open an issue or submit a pull request.
