# RazorPageForm

**RazorPageForm** is a simple and interactive Razor (.cshtml) web page designed to demonstrate server-side form handling using ASP.NET. The page collects user inputs and dynamically displays personalized information along with a selected image upon submission.

---

## Features

- **Form Handling**:
  - Collects user input for the following fields:
    - Name
    - City
    - Address
    - Image selection (via dropdown menu).
  - Processes the form data server-side using Razor syntax.

- **Dynamic Content Display**:
  - Displays a personalized message based on user inputs.
  - Shows the selected image dynamically below the message.

- **Responsive Design**:
  - Styled with basic CSS for a clean and user-friendly interface.

---

## Technologies Used

- **HTML**: For structuring the form and layout.
- **CSS**: For styling the page.
- **C# (Razor)**: For server-side form handling and dynamic content rendering.

---

## Installation

### Prerequisites

- Visual Studio installed on your system.
- .NET SDK installed.

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmed3bdelaziz/RazorPageForm.git
   ```
2. Open the project in Visual Studio.
3. Build and run the project.
4. Navigate to the Razor view that contains the form in your browser.

---

## Usage

1. Open the form in your browser.
2. Fill in the required fields:
   - Name
   - City
   - Address
   - Select an image from the dropdown menu.
3. Click **Submit** to view the dynamically generated message and the selected image.

---

## Example Output

When a user submits the following:

- **Name**: John
- **City**: Cairo
- **Address**: Street 12
- **Image**: Photo 2

The page will display:

```
HELLO John, YOUR CITY IS Cairo, YOUR ADDRESS IS Street 12
[ Photo 2 is displayed below ]
```

---

## Project Purpose

This project was created to:

1. Demonstrate server-side form handling using Razor Pages in ASP.NET.
2. Provide a simple example of dynamic content rendering with user input.
