# WQDropDownMenu
###模仿商品类型选择下拉菜单
使用方法：

    [self.view addSubview:self.dropDownMenu];
    
    self.dropDownMenu.tranformView = self.topImageView;
    
    self.dropDownMenu.dataArray = [DropMenuModel fetchDataArray];
