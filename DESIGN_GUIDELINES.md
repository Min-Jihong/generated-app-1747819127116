# Design Guidelines

{
  "Color System": {
    "Primary Colors": "#4A90E2 for actionable items and highlights",
    "Secondary Colors": "#50E3C2 for minor accents to draw less attention",
    "Accent Colors": "#F5A623 for calls to action and important highlights",
    "Success State": "#7ED321, to indicate a successful action or confirmation",
    "Error State": "#D0021B, for errors or issues that need user attention",
    "Warning State": "#F8E71C, for warnings or cautions",
    "Background Color": "#F4F4F4, for the main background",
    "Surface Colors": "#FFFFFF, for cards, modals, and UI surfaces",
    "Text Colors": {
      "Primary": "#333333 for main text",
      "Secondary": "#666666 for secondary text or placeholder text",
      "Disabled": "#BBBBBB for disabled or unimportant text"
    }
  },
  "Typography": {
    "Font Families": "\"Roboto\", \"Helvetica\", \"Arial\", sans-serif",
    "Font Sizes": {
      "Body": "16px",
      "Headers": {
        "H1": "32px",
        "H2": "24px",
        "H3": "18.72px"
      },
      "Small Text": "14px"
    },
    "Line Heights": {
      "Body": "1.5",
      "Headers": "1.25"
    },
    "Font Weights": {
      "Normal": "400",
      "Bold": "700",
      "Light": "300"
    }
  },
  "Spacing": {
    "Margin and Padding Scales": "8px scale, with values of 8px, 16px, 24px, 32px, etc.",
    "Grid System": "12-column grid, with gutters of 24px",
    "Component Spacing": "Components should have a margin of 16px between them for proper visual separation"
  },
  "Components": {
    "Button Styles": {
      "Primary Button": {
        "Background": "#4A90E2",
        "Text": "#FFFFFF",
        "Border Radius": "4px"
      },
      "Secondary Button": {
        "Background": "#FFFFFF",
        "Text": "#4A90E2",
        "Border": "1px solid #4A90E2",
        "Border Radius": "4px"
      }
    },
    "Input Styles": {
      "Border": "1px solid #CCCCCC",
      "Focused": {
        "Border": "1px solid #4A90E2",
        "Outline": "none"
      },
      "Error": {
        "Border": "1px solid #D0021B",
        "Outline": "none"
      },
      "Placeholder": "#666666"
    },
    "Card Styles": {
      "Background": "#FFFFFF",
      "Shadow": "0 2px 4px rgba(0,0,0,0.1)",
      "Border Radius": "8px"
    },
    "Form Styles": {
      "Label": {
        "Font Size": "14px",
        "Color": "#333333"
      },
      "Input": {
        "Margin": "8px 0"
      },
      "Helper Text": {
        "Font Size": "12px",
        "Color": "#666666"
      }
    },
    "Navigation Styles": {
      "Background": "#4A90E2",
      "Link": {
        "Color": "#FFFFFF",
        "Hover Color": "#3178B7"
      }
    }
  },
  "Animations": {
    "Transitions": "All transitions should be 300ms for consistency",
    "Hover Effects": {
      "Button": "Opacity change to 0.8 on hover for interaction feedback",
      "Card": "Elevate card on hover with a shadow of 0px 4px 8px rgba(0,0,0,0.2)"
    },
    "Loading States": {
      "Spinner": {
        "Color": "#4A90E2"
      }
    },
    "Page Transitions": "Fade-in and fade-out effect for switching pages, lasting 200ms"
  },
  "Responsive Design": {
    "Breakpoints": {
      "Small": "480px",
      "Medium": "768px",
      "Large": "1024px"
    },
    "Mobile-first Approach": "Design for the smallest screen and scale up adding breakpoints",
    "Grid System": "Fluid columns with percentage widths, adapting to the screen size",
    "Component Adaptations": {
      "Button": "Padding and font size adjust for touch targets",
      "Form": "Stack inputs vertically with 100% width for easy mobile access",
      "Navigation": {
        "Mobile": "Collapsed to a hamburger menu",
        "Desktop": "Horizontal menu with hover effects"
      }
    }
  }
}