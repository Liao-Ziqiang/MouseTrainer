# 鼠标点击训练游戏 (Mouse Click Training Game)

这是一个简单的鼠标点击反应训练游戏。用户需要在指定的时间内点击随机出现在页面上的圆点，并且可以自定义圆点的大小和显示间隔时间。游戏会记录点击成功和失败的次数。

This is a simple mouse click reaction training game. Users must click on a randomly appearing circle on the page within a specified time. Users can also customize the size of the circle and the display interval. The game records the number of successful and failed clicks.

## 功能介绍 (Features Overview)

- **圆点随机生成**：圆点会随机出现在页面上，且不会覆盖顶部设置栏或超出页面边界。
  
  **Random Circle Generation**: Circles randomly appear on the page and will not overlap with the top settings bar or exceed the page boundaries.

- **自定义设置**：
  
  **Customizable Settings**:
  - **圆点的最小和最大半径**：用户可以自定义圆点的大小范围（最小半径和最大半径）。
    
    **Minimum and Maximum Circle Radius**: Users can customize the size range of the circle (minimum and maximum radius).
  - **圆点出现的间隔时间**：用户可以设置每个圆点的显示时间，超过时间未点击则计算为失败。
    
    **Circle Display Interval**: Users can set the display time for each circle. If the user does not click the circle within the set time, it will count as a failure.

- **点击计数**：游戏会记录点击成功和失败的次数，并显示在页面右下角。
  
  **Click Counter**: The game records the number of successful and failed clicks, which are displayed in the bottom-right corner of the page.

- **点击目标后自动刷新**：每点击一次圆点，新的圆点会立即生成。
  
  **Automatic Refresh After Click**: Each time the user clicks the circle, a new circle is immediately generated.

- **自适应窗口大小**：当浏览器窗口大小改变时，圆点会自动重新生成，确保其始终在可见区域内。
  
  **Responsive to Window Size**: When the browser window is resized, the circle automatically regenerates to ensure it remains within the visible area.

## 使用方法 (How to Use)

1. **打开游戏**：
   - 将项目代码保存为 `.html` 文件，并在浏览器中打开。
     
     **Open the Game**: 
     - Save the project code as a `.html` file and open it in a browser.

2. **设置参数**：
   - 在页面顶部的设置栏中，您可以调整以下参数：
     
     **Set Parameters**: 
     - In the settings bar at the top of the page, you can adjust the following parameters:
     - **间隔时间(ms)**：设置每个圆点在页面上显示的最长时间（单位：毫秒），超过该时间未点击则记为一次失败。
       
       **Interval Time (ms)**: Set the maximum time each circle will stay on the page (in milliseconds). If not clicked within this time, it counts as one failure.
     - **半径下界(px)**：设置圆点的最小半径（单位：像素）。
       
       **Minimum Radius (px)**: Set the minimum radius of the circle (in pixels).
     - **半径上界(px)**：设置圆点的最大半径（单位：像素）。
       
       **Maximum Radius (px)**: Set the maximum radius of the circle (in pixels).

3. **开始游戏**：
   - 点击“开始”按钮，游戏会随机生成圆点，并开始记录您的点击情况。
     
     **Start the Game**: 
     - Click the "Start" button, and the game will randomly generate circles and start recording your clicks.
   - 您需要在圆点消失之前点击它，每次点击后将立即生成新的圆点。
     
     You need to click the circle before it disappears, and a new circle will immediately be generated after each click.

4. **结束游戏**：
   - 点击“结束”按钮，游戏会停止，并显示您当前的点击成功和失败次数。
     
     **End the Game**: 
     - Click the "End" button to stop the game and display your current number of successful and failed clicks.
