请帮我完善英文翻译！谢谢！
Please help me improve the English translation! thank you!



Twitter https://twitter.com/linlin67601187
Github  https://github.com/origin0110



通过此文件修改设置：
Modify the configuration from this file：
OriginShader/shaders/glsl/Users/Set.txt



贴图的透明度是一个8位二进制数，默认为11111111，或者0xFF
第7位控制金属度，0为金属
第6位控制粗糙度，0为光滑
第5位控制自发光，0为自发光
第4位控制形状，0将 禁 用 自动法线
如果是金属，第3位和第2位为金属F0的索引
你可以自己画你喜欢的pbr贴图

The alpha of the texture is an 8-bit binary number. The default value is 11111111, or 0xFF.
The 7th bit represents metal, 0 for metal.
the 6th bit represents roughness, 0 for smooth.
the 5th bit represents fluorescence, 0 for use fluorescence.
the 4th bit represents normal, 0 for DO NOT use normal mapping.
When it is metal, the 3rd and 2nd bits serve as the index of F0.
You can create your favorite PBR map.