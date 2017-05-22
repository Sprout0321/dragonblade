・解凍してできたファイルはskinディレクトリの直下に入れる。
・pukiwiki.ini.php のユーザーエージェント判定している所にスマホ判定を入れる。（450行目付近）
　（判定文字列はお好みで書き換えて下さい）
 	// スマートフォン判定追記
 	array('pattern'=>'#\b(Android|iPhone)\b#',	'profile'=>'sp'),
・default.ini.phpをコピーしてsp.ini.phpを作る。
・sp.ini.phpを修正する。（17行目付近）
 	define('SKIN_FILE', DATA_HOME . SKIN_DIR . '180wiki-sp.skin.php');
