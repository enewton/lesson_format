# Status

- Builds Python lessons from manifest, transforming markdown into html
- Use pandoc scratchblocks filter to transform scratch into images
- Manifest for Term 1, handling notes and main file, no resources
- Copy across project notes, project materials into project directory
- Copy across term resources into term directory
- Transform any markdown which is a note for a project, or a resource for a term into html
- CCW/UK legal disclaimer
- Clean up and split out CSS
    - make a new template to start from, not lesson_template.html
    - Inject the logo into the document
    - level should only be inserted if there.
- Term, Language, Root Index Created.
- Write links to worksheets, links to terms
- Write links to extra items in project index.
- Generate CCW/CCUK builds
    - Parse arguments..
    - Seperate out colours and styles
    - Split out CSS for lesson, and world scheme.
    - Templated CSS by python, generate when copying across? (heh, sweet)
- Write links to materials for projects.
- Write links to alternative formats for project worksheets
- Let projects link to embedded images
- Add missing headers to markdown project files, in term 1
- Let yaml headers override project materials, notes too
- Add manifest for en-GB term 2 with link to PDFs
- Manifests for en-GB Web Dev, Term 3
- Sort languages by number of projects.
- Add sv-SE to output
- Get classes in directory listings
- Indexes should have proper class names + styles
- More detail in manifest
    - full names of courses/terms
    - introductory schpeil
- Build example term + manifest + project to show it.
- Pass language around instead of lang code? If Possible.
- Internationalization options
    - full names of languages

- Internationalization
    - Use Language to set text like 'Projects'
    - Use Language to set legal text if present

- Zip any supporting materials per project.
    - Python zip lib or use zip -freshen
    
- Unstyled PDF output, add it to index

## Next

- Complete Manifests for en-GB Term 1 2 3 by adding materials.

- Tidy up index styles.
- Print and media queries for pages.

- Tidy up manifests

- Nicer error messages and recovery
- Better argument parsing.

- Document the manifest format/ markdown headers
- README for markup too.

- Move Regions/Languages out of build.py and into json files.
    in templates/ccw.theme templates/ccuk.theme
    in lang/code.lang json

- Custom TeX output for pandoc, to make PDFs look more in-house style.
- Maybe Zip/Bundle up Terms, add them to index - They need to be standalone
