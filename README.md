# PromptView

 ![image](https://github.com/chenpengfei88/PromptView/blob/master/app/src/main/res/drawable/cps.png)

# 如何使用

```
PromptViewHelper pvHelper = new PromptViewHelper(mActivity);
pvHelper.setPromptViewManager(new ChatPromptViewManager(mActivity));
pvHelper.addPrompt(holder.itemView.findViewById(R.id.textview_content));
```

