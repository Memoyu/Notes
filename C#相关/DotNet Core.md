#### 概述

**这是一些笔记**

- 这是哪一项，

- 这是另一项

  ```c#
   private void CheckBox_IsFileCardNum_CheckedChanged(object sender, EventArgs e)
          {
              JudgeConditionEnableOrDisable(CheckBox_IsPid.Checked, TextBox_Pid);
              if (!CheckBox_IsPid.Checked)
              {
                  RemoveDicKeyValueByKey("Pid");
              }
          }
  ```

  

  