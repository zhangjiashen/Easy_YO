branch name: first_android_app

Goals:
Build a simple version of "YO"
See "demo_YO 1.0"

Workflow
0. Create a new project(called "YO"), keep the activity name "MainActivity"(finished)
1. Find "activity_main.xml" in app/src/main/res/layout, change the root element of the layout file into LinearLayout, set its orientation to "vertical", padding to 16dp
2. Add an EditText element into the layout file with id “@+id/edit_text”, width “match_parent” and height “wrap_content”
3. Add a Button to the layout file with id “@+id/button”, width “match_parent”, height “wrap_content” and text “Click me!”
4. There is already a TextView with text "Hello world!", add id field “@+id/text_view”
5. In MainActivity.java, get the EditText, the Button and the TextView using findViewById
6. In MainActivity.java, set the OnClickListener of the button so that when the button is clicked, your program should set the text of TextView to be the value of the EditText