# android-viewpager-sample
Android ViewPager Sample

Add ViewPager to activity_main.xml

Create new Fragment (Blank) FirstFragment

Create new Fragment (Blank) SecondFragment

Create new Fragment (Blank) ThirdFragment

Create new Fragment (Blank) FourthFragment

Subclass FragmentPagerAdapter in MainActivity.java

Set adapter of the ViewPager as follows:

    ViewPager pager = findViewById(R.id.pager);
    SectionsPagerAdapter adapter = new SectionsPagerAdapter(getSupportFragmentManager());
    pager.setAdapter(adapter);
