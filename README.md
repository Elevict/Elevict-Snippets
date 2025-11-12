<p align="center">
<img src="https://github.com/user-attachments/assets/a127591d-92d9-4d05-9d01-414739934a7f" width="500" style="border-radius:8px; box-shadow:0 4px 8px rgba(0, 0, 0, 0.2);"/>
</p>

This collection of CSS snippets is designed to enhance the functionality and appearance of Obsidian MD. These snippets are intended to be used with the [Shade Sanctuary](https://github.com/Elevict/Shade-Sanctuary) theme for optimal results. It is highly recommended to use these snippets in conjunction with the [Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings), or you'll miss out on all the features that the snippets have to offer.

# Snippets Overview
## **Background Animations**
   Adds animated backgrounds with types wave, stripes, and checkerboard.
   
<p align="center">
<img width="280" height="280" alt="Wave" src="https://github.com/user-attachments/assets/40143178-5510-4fb9-904a-9f2b596e0534" />
<img width="282" height="282" alt="Strips" src="https://github.com/user-attachments/assets/2384eaa9-e671-4818-b1f9-257b664282b0" />
<img width="270" height="270" alt="Checkerboard" src="https://github.com/user-attachments/assets/d45af178-80b1-4de6-b8b7-841f7385513c" />
</p>

## **Colored Sidebar Items**
   Customizes colors for sidebar folders and files. Originally by [CyanVoxel](https://github.com/CyanVoxel/Obsidian-Colored-Sidebar), but signifiantly improved and customizable. To apply a specific color to a folder you need to add a numeric prefix such as `00`, `01`, `02`, etc. at the front of the folder names.
   
<p align="center">
<img width="152" height="183" alt="image" src="https://github.com/user-attachments/assets/05f7f84b-53a0-4b9a-ab91-7a9f461c2bbe" />
</p>

## **Gradient Callouts and Headers**  
   Create dynamic homepages and dashboards using gradient callouts and headers. Each gradient callout is part of a unified color palette system that pairs perfectly with matching gradient headers.

   **Notes:**
   1. Format gradient callouts as `[!gradient_x_y]`, where `x` (1–5) selects the gradient palette and `y` (1–17) defines the shade intensity.  
   2. Use `[!multi-column]` to organize gradient callouts into flexible grid layouts.
   3. Many other forms of customization available through Style Settings.

### Example: Gradient Multi-Column Layout
<p align="center">
  <img width="578" height="389" alt="image" src="https://github.com/user-attachments/assets/79e4e381-8407-4e41-b40d-b2fc1dc9e327" style="border-radius:8px; box-shadow:0 4px 8px rgba(0, 0, 0, 0.2);"/>
</p>

```md
> [!multi-column]
>
> > [!gradient_2_3]  Cellular Biology
> >
> > [![[biologyicon.svg]]](Biology.md)
> >
> > Exploring the structure and function of cells, the basic units of life.
>
> > [!gradient_2_6] Psychology
> >
> > [![[psychologyicon.svg]]](Psychology.md)
> >
> > Studying mental processes in an introductory context.
>
> > [!gradient_2_9] Molecular Neuroscience
> >
> > [![[neuroscienceicon.svg]]](Neuroscience.md)
> >
> > Studying the biochemical basis of the nervous system.
>
> > [!gradient_2_12] Neurobiology
> >
> > [![[neurobiologyicon.svg]]](Neurobiology.md)
> >
> > Understanding the structure and function of the nervous system.
```

## Hoverable Dropdown
   Creates a dropdown menu that appears when hovering over a specified element.

### Example: Basic Dropdown
<p align="center">
<img width="488" height="90" alt="image" src="https://github.com/user-attachments/assets/05a914cd-a378-4e72-9cae-6f9ec4347037" />
</p>

```markdown
> [!navmenu|gradient_1_14]
> - Tab 1
>     - Subtab 1.1
>     - Subtab 1.2
>     - Subtab 1.3
> - Tab 2
>     - Subtab 2.1
>     - Subtab 2.2
> 	    - Subtab 2.2.1
```

### Mathematics Callouts
Provides callouts for mathematical theorems, definitions, and problems with seven distinct styles.

<p align="center">
<img width="789" height="245" alt="image" src="https://github.com/user-attachments/assets/178d01a9-bb59-43f7-b9b8-9e387572f52c" />
</p>

```markdown
> [!definition] **Definition** (Joint Probability Density Function)
> Two random variables $X$ and $Y$ are **jointly continuous** if there exists a nonnegative function $f_{XY}: \mathbb{R}^{2} \to \mathbb{R}$, such that, for any set $A \in \mathbb{R}^{2}$, we have
> $$
> P((X,Y) \in A) = \iint_{A}f_{XY}(x, y) \ dx \ dy
> $$
> The function $f_{XY}(x, y)$ is called the **joint probability density function** (PDF) of $X$ and $Y$
```
