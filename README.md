# vortex33
cocos2d-x 3.x RenderMesh bug recorder

这个使用自定义shader的漩涡效果在3.4/3.5/3.6上均会导致VertexBuffer(RenderMesh)相关内存在第一次draw之后被串改（在pollEvents阶段），而奔溃。但是在3.3上正常运行。

Record here, solve later.