1. Hero Title

Centered headline introducing the brand’s core value.

2. Feature Section (Left – Center – Right Layout)

Left: Features like Real Food and Premium Ingredients.

Center: Product image.

Right: Features like Made Fresh and Vet Developed.

Implemented using flexbox (flex-col md:flex-row) for responsive stacking.

3. Guarantee + Logos Section

A call-to-action banner (bg-[#EE6F4B]).

Left: Guarantee with icon.

Right: Brand trust logos.

Responsive with flex-col md:flex-row.

4. Nutrition Highlight Section

Image + Text split into two columns (grid-cols-1 lg:grid-cols-2).

Key stats (97%, 84%, 92%) displayed with emphasis using Tailwind text utilities.

5. Gastrointestinal Health Section

Image and text in a two-column grid.

Rounded images (rounded-lg) for clean visuals.

6. Prebiotics Section

Alternating layout using order-1, order-2 to swap image/text positions on mobile vs desktop.

🛠 Methods & Techniques Used

7. Tailwind CSS via CDN

Used @tailwindcss/browser@4 to quickly apply utility classes without build tools.

8. Responsive Design

Classes like md:flex-row, lg:grid-cols-2, order-1 lg:order-2 make the layout mobile-first and adapt to larger screens.

9. Flexbox & Grid

flex for aligning icons with text.

grid for structured sections with images and content.

10. Spacing & Typography

gap-x, gap-y, my-5, px-6, py-10 for spacing.

font-semibold, text-[#424153], leading-snug for typography.

11. Utility-based Styling

No custom CSS written—everything styled using Tailwind’s utility classes.

Colors (bg-[#EE6F4B], text-[#424153]) applied directly via Tailwind.

12. Images & Assets

Assets stored in /asset/ folder and referenced via <img> tags.

Logos and icons sized responsively with w-12 h-12, h-8 w-auto, etc.

💻 How to Run Locally
13. Clone the repository

git clone https://github.com/isaaccode246/cs-shopify-test.git

14. Navigate into the project folder
cd cs-shopify-test

15. Open home.html in your browser
