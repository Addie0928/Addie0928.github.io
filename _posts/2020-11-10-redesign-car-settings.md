---
title: Redesign car settings
author: Addie Zhang
date: 2020-11-10 11:33:00 +0800
categories: [Blogging, Demo]
tags: [typography]
math: true
---
# Background

This is information architecture redesign.Car setting is the important parts of CSD. These setting items are related to the software, interior or exterior, include power doors, windows or seats, driving assistance (ADAS) or automatic parking.

此项目是信息框架重设计。车辆设置是CSD系统的重要部分，这些设置项与软件、车的外观内饰相关。包括：电动门、车窗、座椅，驾驶辅助(ADAS)、自动泊车等。


# Issues
When testing the initial setting in the real car, we found that users cannot find some specific functions, and complete the tasks with high error rates. Here are some issues we need to follow up:

我们将初始方案在真车上测试，发现用户找不到一些具体的功能，且完成任务时出错率较高. 需解决以下问题：

---

#### 1. Main menus 
   - **Reasonable number.** How many menu items are needed to cover all functions？
   - **Hierarchy.** How to arrange them?  
   - **Classification.** Which sub-menus should be in each main menu?
      
   - 合理的数量。需要几个菜单项能覆盖所有功能？ 
   - 优先级。主菜单各项如何排序？
   - 分类。在每个主菜单下，有哪些次级菜单？

#### 2. Sub menus 次级菜单

   - **Classification.**  Which functions should be in sub menu?
   - **Efficiency.**  How to switch each sub-menu and each main menu quickly.
   
   - 分类。在每个次级菜单下有哪些功能？
   - 效率。每个次级菜单、每个主菜单如何快速切换。

#### 3.Specific functions 具体功能
- **Findable and understandable.** Try not to operate more than 3 times.
 Try not to operate more than 3 times.
- **Error recovery.** How to let users feels comfortable about making mistakes and always being able to recover.

- 可找到、可理解。操作步骤尽量不大于3次。
- 错误恢复。如何使用户在犯错时感到舒适，且总是能恢复正确。

![Initial interface](/assets/img/sample/01_redesign/1_initial interface.png)



# Research
In order to know the market, we did the real car research to understand the current car HMI system. We learned about some design strategies:
   
为了更好了解市场，我们做了真车调研。以下是我们了解到的一些设置项设计策略：

-  **Default value.** For functions that always in one state, sets default values for users. Even remove it.
-  **Little i.** Some details don't need to be explained, remove them or hide them in icon“i” if really need to.
- **Mode.** For functions that are highly correlated and interacted, or have same operation logic, they can be grouped into one mode.
- **3D model.** Car interior, exterior and ambient light related settings, use nice graphics, 3D model or animation. 
- **Customization.** Using ID memory, one single car allows multiple user IDs.
-  **User Academy.** Guide and inspire user to learn the car, give user award to explore and discover.

- 默认。对于总以一个状态出现的功能，为用户设置默认值。甚至删除该设置。
- 对于一些功能细节，不需要向用户解释的可以删掉。如果实在是需要，那就隐藏在小“i”图标里。
- 车内饰、外饰和氛围灯相关的功能，使用炫丽的图形，3D模型或者动画展示。
- 自定义。用ID来记忆设置，一个车辆可以有多个ID.
- 用户学院。引导和启发用户了解车辆，在他们探索发现的过程中给予奖励。

 ![research](/assets/img/sample/01_redesign/2_research.png)


# Iteration proposal
We did the card sortingonline.And did the A/B testing for Initial verion and updated version.
我们做了线上卡片分析, 并且进行A/B测试。 

 ![card ](/assets/img/sample/01_redesign/3_card_sort.png)
 
 ![ab test ](/assets/img/sample/01_redesign/4_ab_test.png)

Specific interface：


 ![ab test ](/assets/img/sample/01_redesign/5_all_pages.png)


---

See report details in [A/B testing](https://www.xxx.com).

---