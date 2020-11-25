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
    
#Table_Layout_Example

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
                android:text="UserId" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="User Name" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Roll.No:" />
        </TableRow>
        <TableRow
            android:background="#DAE8FC"
            android:padding="5dp">
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="1" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Preeti Deswal" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="154" />
        </TableRow>
        <TableRow android:background="#DAE8FC" android:padding="5dp">
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="2" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Abhishek Deswal" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="15" />
        </TableRow>
        <TableRow android:background="#DAE8FC" android:padding="5dp">
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="3" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Kamna Malik" />
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="01" />
        </TableRow>
    </TableLayout>
...
