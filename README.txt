##TODO List

[] `clair.github.io/index.html`: information about the lab
[] ·clair.github.io/pages/research.html`: information about research directions
[] `clair.github.io/pages/join_us.html`: information about joining the lab
[] `clair.github.io/pages/publications.html`:" to add more publications on this page, directly modify the `json` files in `clair.github.io/documents/meta`, with each entry in the following format:
```
<id>: {
    "title": <title>,
    "authors": <An array of authors>,
    "conference": <Conference>,
    "date": <Date>,
    "website": <Website> (optional),
    "video": <Video> (optional),
    "arxiv": <Arxiv> (optional) 
  }
```

Example
```
"llmcognition@icml": {
    "title": "Recursive Introspection: Teaching Language Model Agents How to Self-Improve",
    "authors": ["Yuxiao Qu", "Tianjun Zhang", "Naman Garg", "Aviral Kumar"],
    "conference": "arXiv:2407.18219v2",
    "date": "July 2024",
    "website": "https://cohenqu.github.io/rise.github.io/",
    "video": "https://www.youtube.com/watch?v=Qv8aTLthfhs",
    "arxiv": "http://arxiv.org/abs/2407.18219"
  }
```

A helper function defined in `clair.github.io/assets/js/helper.js` will automatically handle the display.


