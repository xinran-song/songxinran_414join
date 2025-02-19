
## 名字:宋忻然
## 自我介绍
### 我是24级宋忻然，可以叫我小宋。🌟
经过一学期学习，掌握基础c语言编程，非常喜欢数字媒体技术专业，自学了基础建模知识。
## 加入414，我希望通过系统的学习和实践，掌握以下知识：
### 1. **技术技能**
   - **编程语言**：进一步学习与数字媒体相关的编程语言，用于开发交互式媒体应用。
   - **图形处理**：掌握图像处理技术，包括Photoshop、Illustrator等工具的使用
   - **3D建模**：学习使用Blender、Maya等软件进行3D建模和动画制作，理解渲染和光照技术。
   - **视频编辑与特效**：熟练使用Premiere Pro、After Effects等工具进行视频剪辑和特效制作。

### 2. **项目经验**
   - **团队合作**：参与414的学习任务，积累团队协作经验
   - **实际应用**：通过实际项目，将理论知识应用于实践，提升解决实际问题的能力。
   - **作品集**：积累个人作品集，展示在数字媒体领域的技能和成果。

### 3. **资源**
   - **专业指导**：获得老师和学长学姐的指导，了解专业的最新动态和技术趋势。
   - **网络资源**：了解更多专业数据、在线课程和学习平台，


### 4. **职业发展**
   - **实习机会**：通过414，获得实习机会，积累工作经验。
   - **职业规划**：获得职业规划指导，明确未来发展方向，提升就业竞争力。

### 5. **创新与创业**
   - **创新思维**：培养创新思维，学习如何将创意转化为实际项目。
   - **创业支持**：获得创业指导，了解创业流程，参与创业项目，积累创业经验。
## 图片
### ！[图片](D:\.jpg)

## 2.3题
### ![下午茶系列】（C:\Users\木斤斤\Desktop.jpg）
### 设计思路

这张下午茶系列的渲染图旨在营造一个温馨、舒适的下午茶场景，通过丰富的细节和材质表现，增强画面的真实感和视觉吸引力。设计思路围绕以下几个方面展开：

1. **主题与氛围**：以“下午茶”为主题，场景中包含多种食物和饮品，如小熊面包、煎鸡蛋、果酱、苹果、咖啡、花茶等，搭配盆栽、桌布、窗户倒影等元素，营造出轻松、惬意的氛围。
   
2. **细节与真实感**：通过精细的材质和纹理处理，如木质盘子、玻璃果酱瓶、液体咖啡、噪浪纹理的花茶等，增强物体的真实感。同时，通过灯光和窗户倒影的布置，提升场景的光影效果，使画面更加生动。

3. **色彩与渐变**：运用颜色渐变等方式，突出物体的立体感和光影变化，尤其是小熊面包的渐变效果，使其看起来更加柔软和诱人。

4. **层次与构图**：通过不同物体的摆放和层次感，如盆栽、咖啡杯、果酱瓶等，构建出丰富的画面层次，避免单调。

---

### 技术实现

#### 1. **模型建模**
   - **小熊面包**：使用Blender的多边形建模工具，创建面包的基本形状，并通过细分曲面和雕刻工具细化表面细节，使其看起来柔软且有质感。
   - **煎鸡蛋**：鸡蛋的蛋白和蛋黄分别建模，蛋白边缘通过柔化工具处理，使其看起来更加自然。葱花通过插件随机分布，增强真实感。
   - **果酱瓶**：玻璃瓶使用圆柱体建模，瓶口和瓶底通过环切和倒角工具细化。果酱部分使用流体模拟，表现其流动感。
   - **苹果**：苹果果实和杆分别建模，果实通过细分曲面和雕刻工具表现其光滑表面，杆部分通过曲线建模。
   - **盆栽**：植物部分使用Blender的粒子系统生成叶片，花盆通过简单的几何体建模。
   - **咖啡杯**：杯子使用圆柱体建模，液体部分通过布尔运算，表现液体的表面张力。
   - **勺子**：使用曲线建模工具创建勺子的基本形状，并通过细分曲面和倒角工具细化边缘。
   - **桌布**：使用布料模拟工具生成桌布的褶皱效果，调整布料的刚度和重力参数，使其自然下垂。
   - **桌子**：使用简单的立方体建模，边缘通过倒角工具处理。
   - **窗户倒影**：通过平面建模创建窗户，并使用环境纹理贴图生成倒影效果。

---

#### 2. **纹理与材质**
   - **小熊面包**：使用渐变纹理和颜色渐变表现面包表面的光影变化，结合次表面散射材质，增强面包的柔软感。
   - **煎鸡蛋**：蛋白部分使用半透明材质，蛋黄使用光滑材质。木质盘子通过木质纹理贴图和法线贴图表现木纹细节。
   - **果酱瓶**：玻璃瓶使用玻璃材质，调整折射率和粗糙度参数。果酱标签通过UV贴图将2D标签贴合到瓶身。
   - **苹果**：果实使用光滑材质，结合颜色贴图和凹凸贴图表现表面纹理。杆部分使用粗糙材质。
   - **盆栽**：叶片使用透明贴图和颜色贴图，花盆使用陶瓷材质。
   - **咖啡杯**：杯子使用陶瓷材质，液体部分使用液体材质，调整折射和反射参数。
   - **花茶**：使用噪波纹理和颜色渐变表现茶水的波纹效果。
   - **勺子**：使用金属材质，调整粗糙度和反射参数。
   - **桌布**：使用布料纹理和颜色贴图，表现布料的质感。
   - **桌子**：使用木质纹理贴图和法线贴图，表现木纹细节。
   - **窗户倒影**：使用环境纹理贴图生成倒影效果。

---

#### 3. **UV贴图**
   - **果酱标签**：通过UV展开工具将果酱瓶的标签部分展开为2D平面，然后在图像编辑软件中绘制标签图案，最后通过UV贴图将图案贴合到瓶身。
   - **木质盘子**：通过UV展开工具将盘子的表面展开，应用木质纹理贴图，调整UV坐标以匹配木纹的方向和比例。
   - **桌布**：通过UV展开工具将桌布的表面展开，应用布料纹理贴图，调整UV坐标以匹配布料的图案。

---

#### 4. **灯光与渲染**
   - **灯光布景**：使用区域光和环境光作为主光源，模拟自然光效果。通过调整灯光的强度、颜色和角度，增强物体的立体感和阴影效果。
   - **窗户倒影**：通过环境纹理或HDRI贴图生成窗户的倒影效果，调整反射强度和模糊度，使其看起来更加自然。
   - **渲染设置**：使用Cycles渲染引擎，启用全局光照，增强画面的真实感。调整采样率和光线反弹次数，确保渲染质量。

