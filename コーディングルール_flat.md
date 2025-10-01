\# コーディングルール

メンバ変数 先頭は小文字のm\_を付け小文字で記述 例：int m\_count;

ローカル変数
先頭の文字は小文字（分かりにくく、一つの単語で表せない場合、二つ目の先頭単語は大文字）
　　　例：float shotPower;

構造体 先頭の文字は大文字 例：struct Wave{};

クラス 大文字のCを付け先頭文字を大文字にし記載する 例：class CPlayer{};

関数 先頭の単語を大文字、二つ目の単語も大文字
短く分かりやすいように動詞と何かでつける 　　　例：void PlayerMove();

引数 全て小文字 例：void SetPosition(DirectX::XMFLOAT3 position);

定数 マクロでこれまで組んでいたためマクロはだめ？
先頭は小文字のk\_をつけ小文字で記述 　　　　　例：k\_maxspawn

マクロ 全て大文字　二つ以上の単語構成は \_ で記載 　#define SCREEN\_WIDTH

名前空間 全て小文字　二つ以上の単語構成は \_ で記載 例：namespace
data{};

ポインタ pを単語の前につける メンバ変数と一緒の時　Player\* m\_pPlayer;

