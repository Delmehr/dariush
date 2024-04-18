url: http://www.dariushnazari.com
timezone: Iran/Tehran
permalink: /:year/:month/:day/:title.html
markdown: kramdown

kramdown:
  input: GFM
  syntax_highlighter: rouge
  syntax_highlighter_opts:
    block:
      line_numbers: true

sass:
    sass_dir: /assets/css/stylesheets
    style: :compressed

collections:
    projects:
        output: true
        permalink: /:path/

exclude: [vendor]


  
