# qnote

A simple note taking "app"

## Inspiration

A found myself needing to take quick disposable notes during meetings, while coding or just to remember future   
me of what I was doing yesterday.  
In this kind of situations I'm not looking for fancy features (like a gorgeous UI or even synchronization),   
I just need something that runs fast and is ready at my fingertips at any time.

## Instalation

1. Clone the repo in your favourite location (`git clone https://github.com/andresemartinez/qnote.git`)
2. Give grants to the qnote file inside the qnote folder (`chmod +x qnote/qnote`)
3. Add qnote to your path (Add this line to your *rc* file: `export PATH="«path_to_qnote»/qnote:$PATH"`)
4. Source the completion file (Add this line to your *rc* file: `source "«path_to_qnote»/qnote_completion"`)

## Configuration

| Variable        | Description            | Default     |
| --------------- | ---------------------- | ----------- |
| QNOTE_DIR       | Notes home directory   | $HOME/notes |
| QNOTE_EXTENSION | Notes file extension   | md          |
| QNOTE_EDITOR    | Notes editor of choice | $EDITOR     | 


**Pro Tip:** The script is not that long, feel free to change whatever you want to make it suit your needs
