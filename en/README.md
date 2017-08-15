1. Go to App Inventor and select Start a new project from the Projects menu. Give your project a name.
2. In the **Palette** on the left, click **Layout** and drag a **VerticalArrangement** onto the phone screen. 
   ![](PaletteVertArr.png)
3. In the **Properties** pane on the right, click on the **Height** property, select **Fill parent** and click **OK**. Do the same for the **Width** property. 
   ![](PropsHeightWidth.png)
4. Now look in the **Palette** under **User Interface** and drag a **Button** onto your **VerticalArrangement** on the phone screen.
5. Over on the right, under **Components**, click on the _VerticalArrangement1_ component. In the **Properties** pane, change the **AlignHorizontal** and **AlignVertical** both to _Center_. Do you see the button move to the middle of the phone screen?
   ![](VertArrAlignProps.png)
6. Click on _Button1_ under **Components** or click on the button itself. In the **Properties** for _Button1_ change the **BackgroundColor** to _Red_ and the FontSize to 24. Tick the FontBold checkbox as well.  
   ![](ButtonPropsFont.png)
7. Scroll down and change the **Text** property of _Button1_ to "Do not press".
8. Click on the **Height** property and select _pixels_. Type _150_ into the box and click **OK**. Then do the same for the **Width**.
9. Finally, find the **Shape** property and select _oval_.
10. Click the **Add Screen** button near the top of the page. Leave the name as Screen2 and click **OK**.
11. When the new screen loads, find the **Label** component under **User Interface** in the Palette and drag it onto the screen.
12. Under **Properties**, change the **Text** to "This app will self destruct in 5 seconds"
13. Under **Sensors** in the **Palette**, find the **Clock** and drag it onto the screen. It's an invisible component, so you won't see it on the screen!
14. In the **Properties**, change the **TimerInterval** to *5000*.
15. Click **Blocks** in the top right. Click on *Clock1* and take out the `When Clock1.Timer do` block. 
16. Now click **Control** under the **Built-in** blocks and find the `close application` block. Grab it and snap it into your other block.




