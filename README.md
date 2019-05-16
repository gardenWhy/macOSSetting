# macOSSetting
一个我在使用黑苹果的过程中的系统设置的记录

####鼠标设置
########关闭鼠标滚轮加速
关闭

defaults write -g AppleMomentumScrollSupported -bool FALSE

开启

defaults delete -g AppleMomentumScrollSupported
