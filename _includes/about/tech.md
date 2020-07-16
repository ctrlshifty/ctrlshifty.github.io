
## Techical Specifics and Data

This website was created using the static website generator Jekyll. Many of the visualizations and interfaces were created by using Jekyll's ability to query .csv, .yml, or .json files. For instance, the [filtering mechanism for the transcripts themselves]({{'/interviews/transcripts/all.html?filter=revision' | relative_url}}) was created by transforming the transcriptions into a csv file and then adding tags based on the major subjects of the study. 

The [subject visualization]({{'/subjectviz/ | relative_url}}) uses these same mechanisms together with rectanglular svg graphical displays to represent the interviews in a visual manner. The visualization/transcript features have since been packaged up in a tool called [Oral History as Data](https://uidaholib.github.io/oral-history-as-data/) to support others looking for means to publish and analyze oral histories and qualitative interviews. The tool has been used to support other CDIL oral history projects that document the [Idaho LGBTQ community](https://www.lib.uidaho.edu/queered/) and the [Gay Rodeo community](https://voicesofgayrodeo.com) respectively. Documentation and instructions for the tool's use are available on the website.  

The site also incorporates tools and platforms such as the [Oral History Metadata Synchronizer (OHMS)](http://www.oralhistoryonline.org/), [YouTube](http://www.youtube.com/), [Bootstrap](https://getbootstrap.com/) and [lightGallery](http://sachinchoolur.github.io/lightGallery/). 

The [poem generator]({{'/flotsam/poemgen/' | relative_url}}) was created by downloading YouTube transcription files (.sbv) of each interview and transforming them into .csv files that are then randomly arrayed in order to make specific poem shapes and outputs. 

Finally, the [Findings]({{'/findings/ | relative_url }}) page was redesigned in 2020 to use the styles of [tufte.css](https://edwardtufte.github.io/tufte-css/).

## Credits

Illustrations, portraits, and process visualizations were created by Corey Oglesby. The about and findings page were written by Lauren Westerfield, Corey Oglesby, and Devin Becker. Photographs were taken by Devin Becker and Kristin Becker. Devin Becker designed and coded the website.