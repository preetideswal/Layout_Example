# Linear_Layout_Example


...Linear Layout Example

    <?xml version="1.0" encoding="utf-8"?>
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#BCB9B9"
        android:orientation="vertical"
        tools:context=".MainActivity">
        <TextView
            android:layout_width="match_parent"
            android:layout_height="80dp"
            android:background="#E8E2E2"
            android:text="Example Of"
            android:textColor="#070707"
            android:textSize="40sp"
            android:gravity="center"
            android:layout_marginTop="40dp"
            android:textStyle="bold" />
        <TextView
            android:layout_width="match_parent"
            android:layout_height="80dp"
            android:layout_marginTop="10dp"
            android:background="#E8E2E2"
            android:gravity="center"
            android:text="Linear Layout"
            android:textColor="#4C0808"
            android:textSize="40sp"
            android:textStyle="bold" />
    </LinearLayout> 

....

# Relative_Layout_Example

    <?xml version="1.0" encoding="utf-8"?>
    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:paddingLeft="16dp"
        android:paddingRight="16dp" >
        <TextView
            android:id="@+id/text1"
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:textStyle="bold"
            android:layout_marginTop="5dp"
            android:textSize="25dp"
            android:layout_alignParentTop="true"
            android:text="Enter Name" />
        <EditText
            android:id="@+id/name1"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_below="@id/text1"
            android:textSize="25dp"
            android:hint="Preeti Deswal" />
        <Button
            android:layout_width="96dp"
            android:layout_height="wrap_content"
            android:layout_below="@id/name1"
            android:textSize="18dp"
            android:textStyle="bold"
            android:layout_alignParentRight="true"
            android:text="Submit" />
    </RelativeLayout>
...    
    
# Table_Layout_Example

    <TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_marginTop="100dp"
    android:paddingLeft="10dp"
    android:paddingRight="10dp" >
    <TableRow
        android:background="#0079D6"
        android:padding="10dp">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="UserId"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="User Name"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Roll.No:"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="15dp"/>
    </TableRow>
    <TableRow
        android:background="#DAE8FC"
        android:padding="5dp">
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="1"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Preeti Deswal"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="154"
            android:textColor="#070707"
            android:textSize="15dp"/>
    </TableRow>
    <TableRow android:background="#DAE8FC" android:padding="5dp">
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="2"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Abhishek Deswal"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="15"
            android:textColor="#070707"
            android:textSize="15dp"/>
    </TableRow>
    <TableRow android:background="#DAE8FC" android:padding="5dp">
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="3"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Kamna Malik"
            android:textColor="#070707"
            android:textSize="15dp"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="01"
            android:textColor="#070707"
            android:textSize="15dp"/>
    </TableRow>
    </TableLayout>
...

# Absolute_Layout_Example
    
    <AbsoluteLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent">
    <TextView
        android:layout_x="100px"
        android:layout_y="100px"
        android:text="User Name"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textStyle="bold"
        android:textColor="#070707"
        android:textSize="20dp"/>
    <EditText
        android:layout_x="370px"
        android:layout_y="80px"
        android:width="100px"
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:textStyle="bold"
        android:textColor="#070707"
        android:hint=" Preeti"
        android:textSize="20dp"/>
    <TextView
        android:layout_x="100px"
        android:layout_y="230px"
        android:text="Password"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textStyle="bold"
        android:textColor="#070707"
        android:textSize="20dp"/>
    <EditText
        android:layout_x="350px"
        android:layout_y="200px"
        android:width="100px"
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:textStyle="bold"
        android:textColor="#070707"
        android:textSize="20dp"
        android:hint=" ****"/>
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Log In"
        android:layout_x="400px"
        android:layout_y="400px"
        android:textStyle="bold"
        android:textColor="#070707"
        android:textSize="20dp"/>
    </AbsoluteLayout>

...

# Scroll_Layout_Example

    <ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:fillViewport="false">
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        android:orientation="vertical" android:layout_width="match_parent"
        android:layout_height="match_parent">
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 1 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 2 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 3 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 4 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 5 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 6 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 7 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"
            android:text="ScrollView 8 Example" />
        <Button android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginTop="60dp"
            android:text="ScrollView 9 Example"
            android:textStyle="bold"
            android:textColor="#070707"
            android:textSize="20dp"/>
    </LinearLayout>
    </ScrollView>
...

# Nested_Layout_Example

    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#51544511"
    android:padding="20dp"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <TextView
            android:layout_width="match_parent"
            android:layout_height="80dp"
            android:gravity="center"
            android:text="Students Details"
            android:textColor="#000000"
            android:textSize="25sp"
            android:textStyle="bold"/>
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:orientation="vertical">
            <TextView
                android:id="@+id/display_scorea_txt"
                android:layout_width="match_parent"
                android:layout_height="90dp"
                android:layout_marginTop="70dp"
                android:layout_marginBottom="24dp"
                android:gravity="center"
                android:text="Preeti Deswal"
                android:textColor="#000000"
                android:textSize="20sp"
                android:textStyle="bold"/>
            <Button
                android:layout_width="144dp"
                android:layout_height="48dp"
                android:layout_gravity="center_horizontal"
                android:layout_marginBottom="8dp"
                android:text="MCA|||"
                android:gravity="center"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold"/>
            <Button
                android:layout_width="144dp"
                android:layout_height="48dp"
                android:layout_gravity="center_horizontal"
                android:layout_marginBottom="8dp"
                android:gravity="center"
                android:text="5th sem"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />
            <Button
                android:layout_width="144dp"
                android:layout_height="48dp"
                android:layout_gravity="center_horizontal"
                android:layout_marginBottom="8dp"
                android:gravity="center"
                android:text="154"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />
        </LinearLayout>
        <View
            android:layout_width="1dp"
            android:layout_height="match_parent"
            android:layout_weight="0"
            android:background="@android:color/darker_gray" />
        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:orientation="vertical">
            <TextView
                android:id="@+id/text3"
                android:layout_width="match_parent"
                android:layout_height="90dp"
                android:layout_marginTop="70dp"
                android:layout_marginBottom="24dp"
                android:gravity="center"
                android:text="Abhishek Deswal"
                android:textColor="#000000"
                android:textSize="20sp"
                android:textStyle="bold"/>
            <Button
                android:layout_width="144dp"
                android:layout_height="48dp"
                android:layout_gravity="center_horizontal"
                android:layout_marginBottom="8dp"
                android:gravity="center"
                android:text="BCA|"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />
            <Button
                android:layout_width="144dp"
                android:layout_height="48dp"
                android:layout_gravity="center_horizontal"
                android:layout_marginBottom="8dp"
                android:gravity="center"
                android:text="1st sem"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />
            <Button
                android:layout_width="144dp"
                android:layout_height="48dp"
                android:layout_gravity="center_horizontal"
                android:layout_marginBottom="8dp"
                android:gravity="center"
                android:text="10"
                android:textColor="#000000"
                android:textSize="25sp"
                android:textStyle="bold" />
        </LinearLayout>
    </LinearLayout>
    <Button
        android:layout_width="150dp"
        android:layout_height="150dp"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_gravity="center_horizontal"
        android:layout_marginBottom="32dp"
        android:gravity="center"
        android:text="ADD More data"
        android:textColor="#000000"
        android:textSize="25sp"
        android:textStyle="bold"/>
    </RelativeLayout>
...

    
