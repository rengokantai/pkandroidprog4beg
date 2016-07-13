#### pkandroidprog4beg
#####Chapter 19. Using Multiple Fragments
######The dual-Fragment address book
res/values/refs.xml:
```
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <item name = "activity_dualfragment" type= "layout">
        @layout/activity_main
    </item>
</resources>
```
res/values-land/refs.xml:
```
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <item name = "activity_dualfragment" type= "layout">
        @layout/activity_main_land
    </item>
</resources>
```
MainActivity
```
@Override
protected void onCreate(Bundle savedInstanceState) {
  super.onCreate(savedInstanceState);

  setContentView(R.layout.activity_dualfragment);
}
```
