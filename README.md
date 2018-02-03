# FakeNews
**FakeNews** is a news app similar to Apple's 'News' App in iOS. The goal of this assignment is to practice `UITableView` and `UITableViewController`.

**Avg. time to develop (beginners):** 2-3 hours

***

## Video Walkthrough

<img src='/FakeNews/demo.gif' width='' />

***

## Before you begin

1. Create a new iOS project
2. Save it as `FakeNews`
4. Download [these images](/FakeNews) and save them to your assets folder on your XCode project.

***

## Required Features

### Overview
Make an app similar to Apple's News app. The `HomeTableViewController` displays random news with random layouts. Some `UITableViewCell`s take user to the `DetailTableViewController`. Feel free to use Apple's News app as a guide along with the video walkthrough above.

**Important Note:** Make sure to design this entire app in **STATIC** `UITableView` and **not** dynamic.

### `HomeTableViewController`

Top                        |  Bottom
:-------------------------:|:-------------------------:
![](/HomePage1.png)        |   ![](/HomePage2.png)


* Contains a total of 5 cells:
  * Cell @ Row 0: Date on the left side, FakeNews Logo on the right side
  * Cell @ Row 1: Second cell: Large `UIImageView` with a news company logo `UIImageView` underneeth that image. Also contains a `UILabel` to display title for the article.
  * Cell @ Row 2: Third cell: Contains two `UIImageView`s as well as `UILabel`s side-by-side.
  * Cell @ Row 3: `UILabel` on the left and a `UIImageView` on the right. Also include `UIImageView` on top of the `UILabel` to display news logo
  * Cell @ Row 4: Same as cell @ Row 3
* Non-selectable cells: Cell @ Row 0 & Cell @ Row 2
* Selectable cells: Row 1, Row 3, Row 4
* Tapping on cell @ Row 1, 3 & 4 should take you to `DetailTableViewController` (see below).
* Make sure to design these well (see below for design tips).

### `DetailTableViewController`

![](/DetailPage.png)

* Contains 3 cells:
 * Cell @ Row 0: Headline `UIlabel`
 * Cell @ Row 1: Large `UIImageView` to display article's image
 * Cell @ Row 3: Large `UILabel` for article's text

***

## Design Tips

### Font Style
![](/Design%20Tips/font-style.gif)



