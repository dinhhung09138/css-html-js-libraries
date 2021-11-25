# The content

The course from [Pluralsignt](https://app.pluralsight.com/course-player?clipId=3c602c02-ac11-4bd8-9b1d-bd4ab842267a)

## Understanding the flexbox container

**Flexbox Container** is the parent object and contains flex items inside of the parent container. We also have the ability to define attributes on the flex container to define the direction and layout of the container

- The children of the flexbox container can be layout in either the horizontal or vertical directions easily and even flex theire size by growing to fill the content area or shrinking their size automatically to flex to any size.

- You can even nest flex containers within other flex items to get more complex layouts within your web pages.

- The CSS flexbox makes it easier for us to distribute space and align content make our web pages responsive without having to write a lot of complex code or adopt these large frameworks within our webpages.

- This hepls adapt and change contnet based on the screen size so the user sees the best layout for whatever size they may be on.

**Defining direction with Rows and Columns** Flexbox stack can be defined by the rows or columns, The flex direction can establish the direction of the flex items. Thes directions are defined by either rows or columns

- The direction really defines how the flex items will be laid out within the flex container itself.

**Horizontall direction** If you don't set the direction, the default is **rows**. For row direction, It can be laid on the left to the right or from right to left. We dont have to defnie the children to be any certain size or event wrap them in a certain div tag. The flexbox container just takes the primary children in the default size and aligns them horizontally

**Vertically direction** it will take the flx items and stack them vertically. The first child will take the whole width and stacks the next flex item right bellow it.

**Main and Cross axes**. It's important to understand how the flex items are either aligned along the main axis or positioned along the cross axis in the flex container. A flex item's width or height will determine the main size of the cross size. You can overwrite the cross size and the main size if needed

- When we use a flex row container, the main axis is the primary axis and will run left to right or right to left depending on the direction we establish in the container. The start of the main axis is called the main start and then the main end is where the items will end. We can set justify content or spread out content to take up speace evenly, we will need to adjust properties and those properties depend on if we're using a row or a column

- If we use column, the main axis will run from top to bottom or bottom to top.

**Flex items** are primary objects within the flex container. The primary objects can be div, images, form, etc. It is the primary item and not the nested children of the flex items

## When not to use Flexbox

- Complex applications (CSS grid)
- Better suited for components
- Control over order
- Complex text layout
