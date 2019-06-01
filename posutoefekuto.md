# ポストエフェクト

## ポストエフェクト用のシェーダーを設定する

```cpp
class MyPostEffectShader : public FragmentShader
{
public:
    
}
```



```cpp
void init()
{
    MyPostEffectShader shader();
    shader.set_param_1( 123.f );
    shader.set_param_2( 456 );
    
    get_graphics_manager().set_post_effect_shader( shader );
}
```

```text


```

