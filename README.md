# Ankimin

**Ankimin** is a collection of **beautiful, minimal card templates** for Anki. These themes are designed to be clean, distraction-free, and elegant – allowing you to better focus while revising.

There are currently three templates, for Basic, Cloze and Image Occlusion cards. They are designed with light and dark theme options, and work well with other plugins, including [Ankipedia](https://github.com/ctrlaltwill/ankipedia) and Image Occlusion Enhanced.

Here is an example of a vanilla Ankimin card (with Ankipedia running concurrently):

![Ankimin Basic Card](https://github.com/ctrlaltwill/Ankimin/blob/main/Demo%20Images/Basic-Preview-Back-Plus-Ankipedia.png)

Each folder in this repository corresponds to a different card-type and contains:
- A **Front** template (`CARDTYPE-front-template.html`)
- A **Back** template (`CARDTYPE-back-template.html`)
- A **Styling** file (`CARDTYPE-template-styling.css`)

Use these to create your own themed note types in Anki.

## How to Create a New Card Template in Anki

1. **Open Anki**
2. Go to **`Tools` > `Manage Note Types`**
3. Choose an existing note type or click **`Add`** to create a new one (it may be easier to duplicate a previous similar card-type – Basic, Cloze or Image Occlusion)
4. Select the note type and click **`Cards…`**
5. You’ll see three fields:
   - **Front Template**
   - **Back Template**
   - **Styling**

## Using an Ankimin Theme

To apply a theme from this repository:

1. Open the folder of your chosen theme (e.g., `Cloze`)
2. Open the three files:
   - `cloze-front-template.html`
   - `cloze-back-template.html`
   - `cloze-template-styling.css`
3. Copy and paste:
   - The contents of `cloze-front-template.html` → into the **Front Template** field
   - The contents of `cloze-back-template.html` → into the **Back Template** field
   - The contents of `cloze-template-styling.css` → into the **Styling** field
4. Adjust the theme to light or dark (outline below)
5. Click **`Save`** in Anki
6. Repeat for other card tips e.g. `Basic`, `Image Occlusion`

## Customization Tips

- Preview your cards as you make changes
- You can tweak colours, spacing, or fonts in the `style.css` file
- To switch between light and dark mode, change the class on the main `<div>`:
  - Light mode: `<div class="ankimin-flashcard card light">`
  - Dark mode: `<div class="ankimin-flashcard card dark">`

## Notes

- Always **save** your changes before exiting
- Consider **backing up** your card-types before applying a new theme

## Screenshots

#### Basic Card – Front ![Ankimin Basic Card](https://github.com/ctrlaltwill/Ankimin/blob/main/Demo%20Images/Basic-Preview-Front.png)

#### Cloze Card – Dark Theme ![Ankimin Cloze Card](https://github.com/ctrlaltwill/Ankimin/blob/main/Demo%20Images/Cloze-Preview-Dark.png)

#### Image Occlusion Card – Front ![Ankimin Basic Card](https://github.com/ctrlaltwill/Ankimin/blob/main/Demo%20Images/Occlusion-Preview-1.png)

## Acknowledgements

Ankimin is built upon and inspired by the excellent work of **Deshai Pranav** and his [Prettify](https://github.com/pranavdeshai/anki-prettify) framework. 

