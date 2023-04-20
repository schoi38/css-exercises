# Margin and Padding practice

For this first exercise, simply edit the `style.css` file so that the divs look like the image below. Only edit the CSS where instructed in the file.  You should only have to change the values of the margin and padding for this exercise. You should not have to add or remove properties in the CSS, or touch the HTML.

![outcome](./desired-outcome.png)

### Self-check 
Use this section to check your work. On _these_ projects, your goal isn't to attain 100% pixel perfection, but to use the tools you've learned to get relatively close to the desired output.

- Div One and Div Three have 32px between their text and border.
- Div One has 12px between it and any other element on the page.
- There is a 48px gap between Div Two and Div Three.
- Div Three is aligned to the right.
- Div Three's alignment is achieved using `margin` (and not float, flexbox, etc.).

# POST

I learned:
- that when there's only block elements, you only need to add margins to one of the adjacent boxes/elements. Since they're going to collapse anyways, you only need to set margins for one of the adjacent boxes. It'd be redundant otherwise.
- further how "margin: auto" operates. Yes, it's usually zero, but ti can also be whatever space is available on that side of the element. This trick can be used to align a box to the right or left (and maybe the top or bottom?).