# CollapsingTitleLayout
Custom layout for 2 animated titles into CollapsingToolbarLayout

## Screenshots
![screenshot](https://raw.githubusercontent.com/nikartm/Android-Widget/master/screenshots/)

## How to use?
Adjust the xml view [Example](https://github.com/nikartm/Android-Widget/blob/master/app/src/main/res/layout/activity_main.xml):
```
<android.support.design.widget.CoordinatorLayout>
    <android.support.design.widget.AppBarLayout>
        <android.support.design.widget.CollapsingToolbarLayout>
            <android.support.v7.widget.Toolbar />

            <ru.nikartm.support.widget.CollapsingTitleLayout
                android:id="@+id/titleLayout"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:paddingTop="75dp"
                app:ctl_textTitle="@string/title"
                app:ctl_titleTextSize="34sp"
                app:ctl_titleColor="@color/colorWhite"
                app:ctl_textSubtitle="@string/subtitle"
                app:ctl_subtitleTextSize="16sp"
                app:ctl_subtitleColor="@color/colorWhite"
                app:layout_collapseMode="parallax"
                app:layout_collapseParallaxMultiplier="0.8" />

        </android.support.design.widget.CollapsingToolbarLayout>
    </android.support.design.widget.AppBarLayout>
</android.support.design.widget.CoordinatorLayout>
```