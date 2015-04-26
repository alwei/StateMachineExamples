◆Unreal Engine 4でブループリントのステートマシンを実現するサンプル

作成Ver UE 4.7.6 English

◎解説
UE4.7にて追加されたブループリント コンポーネントと、更にブループリント インターフェースを使用し、
汎用的なステートマシンを実現するサンプルです。

フォルダー内に用意されている、『StateMachine』フォルダーを他プロジェクトに移行する事で使用できます。
『Examples』フォルダーには使用例となっているブループリントとアセットが格納されています。

◎基本的な使用方法
『StateMachineComponent』をブループリントアクターにコンポーネントとして追加します。
これがステートマシン全体の管理を司ります。
次に『StateComponent』を継承したブループリントコンポーネントを新規作成します。
これが個々のステートを実現するコンポーネントとなります。
作成したコンポーネントは必要に応じてブループリントアクターにコンポーネントとして追加しておきます。

あとは必要なステートに応じて同様のステートコンポーネントを追加します。
ステートコンポーネント内では自由にロジックを作成する事ができ、
『TransitionState』を使って簡単に別ステートへと遷移する事が出来ます。
具体的な使用例は『LandEnemyBP』や『FireEnemyBP』を参考に。

◎プロジェクト全体について
基本的にアセットに関してはフリー素材として使用が可能です。
自由に改変して使っていただいて構いません。
また、プロジェクトを改変して公開する場合にはメールやTwitterなどで一報をいただけると嬉しいです。

このプロジェクトはステートマシンとしてのAIの実装例だけでなく、2Dアクションゲームとしての最低限のサンプルや
ブループリント コンポーネントの使い方、ブループリント インターフェースの使い方など、
様々な部分で実用的になるように考えて作っているつもりですので、ぜひ参考にしてください。

そしてここからわかったテクニックなどがありましたら、ぜひ私にも教えてください。

◎連絡先
Twitter : aizen76
mail : altaizen76@gmail.com
