# Miles

## mMonitor Application

#### Copy database to sd card:

1. Start export using menu overflow (top right 3 dots)
1. display toast when exporting is done

![image](mMonitor/exportDB.gif)

#### Start and stop service

Note:

1. Notifications in the upper left corner.
1. Home button press and return via recently used apps
(preserve the service running state state)

![image](mMonitor/startStopService.gif)

## mConnect Application-Social

### Using menu overflow (top right - three dots)

1. Copy graph data to sd card

    ![image](mConnect-Social/_menu/menu_copy_graph_db.gif)
1. Change day

    ![image](mConnect-Social/_menu/menu_change_day.gif)
1. Reply to messages

    ![image](mConnect-Social/_menu/menu_create_discussion.gif)
1. Note the changes in menu options as tabs are being switched

    ![image](mConnect-Social/_menu/menu_tab_changes.gif)

### Using tabs

#### Progress tab

### No data

Note: Try to find some library which does this graph drawing nicer. Current
implementation simply draw lines and rectangles and fill them with simple colors.
It looks kinda too simple. There must be some lib for this. Find it!!

1. Day View

    ![image](mConnect-Social/_tabs/day.gif)
1. Week View

    ![image](mConnect-Social/_tabs/week.gif)
1. All View

    ![image](mConnect-Social/_tabs/all.gif)

### With Data generated

**Currently verifying if the data displayed is valid/useful**

<img src="mConnect-Social/with_data_week.png" width="300" height="534">

<img src="mConnect-Social/with_data_all.png" width="300" height="534">

1.

#### Messages tab

1. Message reply functionality (tap on message)
1. Expanding discussion functionality (tap on discussion)
1. Difference between message and discussion is that message have no arrow on left side
    * Is this enough?
    * Do we wanna change this?

    ![image](mConnect-Social/_tabs/message_reply.gif)

1.
    ![image](mConnect-Social/_tabs/faq_tab_navigating_animations.gif)



## mTrack Application



## mSmiles Application

* Menu items have same functionality as in other apps. Finish button exits the app.
* Export db export data to sd card.

#### History tab

* Displays levels for every day with image
* Note the scrolling behaviour (swipe left-right)
* Change days can be also done using left right arrows

![image](mSmiles-Affect/smiles_history.gif)

#### Travels tab

After being active, you are visiting cities around the world (no Serbian City - bug :) ).
All of the visiting cities are shown here with the date when you reached it.


![image](mSmiles-Affect/smiles_travels.gif)

#### Play tab

* Animations.
* Dragging the stick use case (works ok).
* Problem with simple tap on the screen. Bird goes to fetch but stick is falling down.
* **Will work on fixing that after refactoring.**


![image](mSmiles-Affect/smiles_play.gif)

#### FAQ tab

* Button feedback behaviour.
* Workflow
* Animations after arrow clicks.
* Animations after list item click (click with yellow background).

![image](mSmiles-Affect/smiles_faq.gif)