# CSS Exercises

These exercises consist of a series of CSS-related tasks intended to complement the HTML and CSS content on The Odin Project (TOP). They should only be completed when instructed during the course of the curriculum.

When doing these exercises, please use all documentation and resources you need to accomplish them. You are _not_ intended to have any of this stuff memorized at this point. Check the docs, use Google, and do what you need to do (besides checking the solutions) to get them done.

> [!IMPORTANT]
> We encourage you to practice your git skills by committing your changes and pushing them to your own fork.  However, please **DO NOT** open a Pull Request to have your solutions merged into this repo or to show your solution.  If we were to merge your changes the exercises would no longer be available as intended for new learners, and opening a PR only causes additional work for us, as we have to close it without merging.

## Contributing

If you have suggestions to improve an exercise, ideas for a new exercise, or notice an issue with an exercise, please feel free to open an issue after thoroughly reading our [contributing guide](https://github.com/TheOdinProject/.github/blob/main/CONTRIBUTING.md).

## How To Use These Exercises

1. Fork and clone this repository. To learn how to fork a repository, see the GitHub documentation on how to [fork a repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
    - Copies of repositories on your machine are called clones. If you need help cloning to your local environment, you can learn how from the GitHub documentation on [cloning a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
1. Go to an exercise directory and open the HTML file in a web browser. You can open the file directly or use something like VSCode's Live Server extension.
1. For each exercise, read the README thoroughly before starting any work.
    - Each README has a "Self Check" list. Use this to ensure you haven't missed any important details in your implementation.
1. Make your edits in the `index.html` and/or the `style.css` files in order to make the output in your browser look like the Desired Outcome image(s).
    - Depending on the instructions of the exercise, you may only need to make edits in one of these files.
1. Once you successfully finish an exercise, check TOP's example solution.
    - You should not be checking the solution for an exercise until you finish it!
    - If your solution differs from TOP's solution (and still passes the exercise's requirements), that is completely fine. The provided solution is only an example and there are always multiple approaches. Feel free to ask in our Discord if there are parts of the example solution you do not understand.

> [!IMPORTANT]
> Do not submit your solutions to this repo, as any PRs that do so will be closed without merging.

## Some Hints
- The provided example solutions put all changes at the _end_ of the CSS file, which may duplicate some selectors (e.g. there might be a `body {}` in the given CSS and another `body {}` in the solution). When you are working on an exercise, it is best practice to add your CSS to existing selectors instead of duplicating them at the end of the file. We're sacrificing this best practice in our official solutions to make it extra clear to you what things we changed to solve the exercise.
- 
- Unless listed in the self-check section, do not worry about getting the exact pixel value for things like margin, padding and font size. These exercises are intended to test your knowledge of CSS, not your ability to guess that a screenshot is using `font: sans-serif bold 16px` or that the margin is _exactly_ `42px`.
- You may need to add some elements to your HTML to get things into the right spot. (For the first few exercises, we make it explicit when this needs to happen.)
- You may need to add more selectors to your CSS file. The first few exercises have almost everything already done for you, but as you progress, you'll find that you need to add more and more selectors to get the correct result.


---

## 🌟 Additional Contribution 

As part of my open-source learning journey, I forked this repository to explore and better understand CSS through real-world exercises.  
This contribution adds learning tips, resources, and notes that can help new learners study CSS more effectively.

---

## 🎨 CSS Learning Tips

Here are some practical tips to improve your CSS skills while working on these exercises:

- 🧩 **Start small and build up:** Focus on one concept (like Flexbox or colors) each time.  
- 🎯 **Focus on layout first:** Master positioning, margin, padding, and display properties before decoration.  
- 🧠 **Understand the “why”:** Before copying a snippet, take time to understand what each line does.  
- 🔍 **Use DevTools effectively:** Right-click → “Inspect” to test CSS changes live in your browser.  
- ⚙️ **Consistent spacing:** Use a system like 4px, 8px, 16px, 32px for visual harmony.  
- 🎨 **Experiment with colors:** Use [Coolors](https://coolors.co/) or [Color Hunt](https://colorhunt.co/) for matching palettes.  
- 💬 **Comment tricky parts:** Add short comments to explain layout logic or selectors.  
- 🪄 **Learn by recreating:** Rebuild simple websites using only CSS to build confidence.  
- 🔁 **Repeat for mastery:** Repetition builds CSS fluency and speed.  
- 📚 **Check compatibility:** Use [Can I use](https://caniuse.com/) to verify browser support.  

---

## 🌐 Useful CSS Resources

- [MDN Web Docs – CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks)  
- [Flexbox Froggy](https://flexboxfroggy.com/) – Practice Flexbox through a fun game.  
- [Grid Garden](https://cssgridgarden.com/) – Learn CSS Grid interactively.  
- [CSS Tricks](https://css-tricks.com/) – A massive library of CSS guides and articles.  
- [The Odin Project – Foundations](https://www.theodinproject.com/paths/foundations) – Review HTML/CSS fundamentals.  

---

## 💡 Example: Simple Button Styling

```css
button {
  background-color: #4CAF50;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s ease;
}

button:hover {
  background-color: #45a049;
}

-Common CSS Mistakes to Avoid
❌ Using too many !important rules.
❌ Forgetting to reset browser defaults (margin, padding).
❌ Poorly organized CSS (group related selectors).
❌ Ignoring mobile responsiveness — always test on smaller screens.
❌ Overusing fixed widths instead of flexible layouts.
🧠 Personal Reflections
Working on this repository helped me better understand how CSS shapes the structure and flow of a webpage.
Every property — from margin to flex — contributes to the overall logic of design.
Through experimenting with layouts and colors, I realized that CSS is not just about appearance; it’s about communicating structure visually.

This project deepened my appreciation for open-source learning, where small contributions can help others grow as well.

🏁 Final Note

Keep your CSS clean, readable, and consistent.
Great CSS comes from clarity, not complexity.
Every small experiment brings you closer to mastering front-end development
