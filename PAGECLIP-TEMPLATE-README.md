# Pageclip Template for Form-atter

This template provides a ready-to-use HTML form integrated with Pageclip for collecting survey responses without requiring a backend server.

## Features

- **Complete Survey Form**: Includes various question types (multiple choice, ratings, checkboxes, dropdowns, text fields)
- **Conditional Logic**: Dynamic form behavior based on user responses
- **Responsive Design**: Works well on desktop and mobile devices
- **Real-time Validation**: Immediate feedback for form validation
- **Professional Styling**: Clean, modern appearance
- **Pageclip Integration**: Ready for form submission handling

## Setup Instructions

### 1. Get Your Pageclip Account
1. Visit [Pageclip.co](https://pageclip.co) and create a free account
2. Create a new site in your Pageclip dashboard
3. Copy your unique Pageclip key

### 2. Configure the Template
1. Open `pageclip-template.html`
2. Replace `YOUR_PAGECLIP_KEY` in the form action with your actual Pageclip key:
   ```html
   <form action="https://send.pageclip.co/YOUR_ACTUAL_KEY_HERE" class="pageclip-form" method="post">
   ```

### 3. Customize the Form
- **Survey Title**: Update the title and description in the `.survey-header` section
- **Questions**: Modify, add, or remove question groups as needed
- **Styling**: Customize the CSS to match your brand colors and fonts
- **Form Fields**: Add or remove form fields based on your requirements

## Question Types Included

### 1. Text Input Fields
- Name, email, occupation fields
- Text areas for open-ended responses

### 2. Multiple Choice (Radio Buttons)
- Single selection questions
- Conditional follow-up questions

### 3. Rating Scales (Likert Scale)
- 5-point satisfaction rating
- Horizontal layout with labels

### 4. Multi-select (Checkboxes)
- Multiple selection options
- Feature importance questions

### 5. Dropdown Menus
- Frequency selection
- Compact option lists

## Conditional Logic Features

The template includes smart form logic:

- **Conditional Fields**: Additional questions appear based on user selections
- **Follow-up Questions**: Show improvement suggestions for dissatisfied users
- **Dynamic Validation**: Real-time form validation with visual feedback

## Form Validation

- **Required Field Validation**: Ensures essential fields are completed
- **Email Format Validation**: Validates email addresses
- **Real-time Feedback**: Visual indicators for validation errors
- **Custom Error Messages**: User-friendly error handling

## Customization Guide

### Adding New Questions
1. Create a new `.question-group` div
2. Add appropriate form fields with unique `name` attributes
3. Update the JavaScript if conditional logic is needed

### Styling Modifications
- Colors: Update CSS custom properties in the `<style>` section
- Fonts: Modify the `font-family` declarations
- Layout: Adjust padding, margins, and responsive breakpoints

### JavaScript Customization
- **Conditional Logic**: Modify the event listeners for new conditional fields
- **Validation Rules**: Add custom validation for specific fields
- **Submission Handling**: Customize success/error message behavior

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Privacy and Security

- All form data is submitted directly to Pageclip's secure servers
- No sensitive data is stored in the template
- HTTPS encryption for all form submissions
- GDPR and privacy regulation compliant when used with appropriate privacy policies

## Troubleshooting

### Form Not Submitting
1. Verify your Pageclip key is correct
2. Check browser console for JavaScript errors
3. Ensure all required fields are filled

### Styling Issues
1. Check for CSS conflicts with existing stylesheets
2. Verify responsive design on different screen sizes
3. Test cross-browser compatibility

### Conditional Logic Not Working
1. Ensure JavaScript is enabled
2. Check for naming conflicts in form fields
3. Verify event listeners are properly attached

## Support

For Pageclip-specific issues, visit [Pageclip Support](https://pageclip.co/support)

For template customization help, refer to the inline code comments and this documentation.

## License

This template is released under the same license as the form-atter project (MIT License).