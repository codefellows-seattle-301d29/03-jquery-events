#### Single-line Summary
**Today, Gene and I (Christian) paired together. It took about 4 hours.**

#### Reflect and summarize on your process for each `TODO` item :  
  1. Gene was late today, so I started the lab off. The first TODO was to add another data attribute to the article object called "data-author." This was to be used for the filter.
  2. Next, we refactored variables within the populateFilters method to template literals (also known as string interpolation) rather than excessive string concatenation. 
  3. Next, we completed handleAuthorFilter/handleCategoryFilter methods. These two were very similar, both using similar jquery lines to complete the same objective (to fade in articles as you click, and hide the rest of the articles).
  4. Next, we worked on the handleMainNav method. The purpose of this method is to show the about me page when you click about, which also should hide all the articles. When you click back to home, the articles are shown again, with a fadeIn(). 
  5. Finally, we worked on the setTeasers method. The purpose of this method is to have all articles partially hidden on page load. They each have a "Read on" button, which we needed to delegate an event to to have it show the rest of the article. When you click Read on, that button also gets hidden. 

#### Checklist (before submitting, fill in each set of square brackets with an 'x')
- [x] We have titled the Pull Request similar to our branch name (ex: 'brian-rick'). 
- [x] This PR includes commits from both myself and my partner; e.g. We followed good pair programming practices by switching driver/navigator roles.
- [x] There is no extraneous, unrelated code included in this PR.
- [x] We have summarized our `TODO:` process above.
