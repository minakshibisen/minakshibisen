- 👋 Hi, I’m @minakshibisen
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
minakshibisen/minakshibisen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
  <RelativeLayout
            android:id="@+id/header"
            android:layout_width="match_parent"
            android:layout_height="?attr/actionBarSize"
            android:background="@color/colorPrimary"
            android:orientation="horizontal">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_centerInParent="true"
                android:fontFamily="@font/poppins_bold"
                android:text="Pending Lead"
                android:textColor="@color/white"
                android:textSize="@dimen/_14sdp" />

            <ImageView
                android:id="@+id/image_back"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_alignParentStart="true"
                android:layout_centerVertical="true"
                android:padding="@dimen/_10sdp"
                android:src="@drawable/ic_back" />

        </RelativeLayout>
