# Sound

```cpp
#include <JumpSound.h>

void GamePlayScene::init()
{
    jump_sound_ = SoundResource( "jump.wav" );
}

void GamePlayScene::on_player_jump()
{
    Sound( jump_sound_ ).play();
}
```

