# Kanban Card Maker
[Card Maker](https://github.com/nhmkdev/cardmaker) project to generate Kanban board cards and labels. Generates cards and labels from .csv files.

Built with [v0.99.3.0](https://github.com/nhmkdev/cardmaker/releases/tag/v.0.99.3.0) of Card Maker

## Examples
### Example Card
<img src="examples/Card_1.png" width="400" style="border:1px solid black"/>

### Example Label
<img src="examples/BoardLabel_3.png" width="400" style="border:1px solid black"/>

### Example PDF
All cards and labels can also be generated into a PDF. [Here is an example](examples/board.pdf) (skip past first blank page)

## Set up

1. Install [Card Maker](https://github.com/nhmkdev/cardmaker)
2. Install fonts (see README in fonts folder)
3. Edit _Cards.csv_
4. Edit _Labels.csv_
5. Start _Card Maker_ and load the _KanbanCards.cmp_ project file
6. From _Layout_ menu select _Reload References_ (or press F9)
7. From _File_ menu select _Export Project to Images_ or _Export Project to PDF_ (See below for on how to adjust PDF output)
 
## Tweaking the output
The cards and labels are set up to take up half an A4 page in portrait at 150dpi, so 2 cards or labels per page. Use the _Layout Control_ panel to for the _Layouts_ if you wish to adjust these (you will need to reposition the layout elements.

### Turning borders on or off
Under _Tools_ | _Settings_ you can turn on or off the _Print/export Layout border_ option

### Setting up PDF output
Under _Tools_ | _Settings_ | _PDF Export_ set the following options:

* _Page Width_ = 8.27
* _Page Height_ = 5.85
* _Page Horizontal Margin_ = 0
* _Page Verticle Margin_ = 0
* Uncheck _Auto-Center Layouts_
* Uncheck _Print Layouts on New Page_

When printing the PDF, select A4, 2 pages per page, single sided, portrait mode.



