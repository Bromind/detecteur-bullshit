
# Détecteur de bullshit

## Pourquoi ?

Le bullshit consiste à faire passer un discours vide pour un discours intelligent (au sens de « qui apporte quelque chose de nouveau »). J'ai pu constater qu'il y a une bonne correlation entre la forme du discours et le fait que celui-ci soit du bullshit (J'admet cette hypothèse, probablement correcte, mais je n'ai pas de données chiffrées pour justifier ce propos, de part la définition informelle de « bullshit »).

Or, je lis de plus en plus (en proportion) d'article bullshit. J'en déduis donc qu'il y a de plus en plus de bullshit sur le net (pareil, j'admet cette hypothèse, somme toute assez raisonnable).

Je me pose donc la question : « Est-ce que les auteurs de ces articles sont au courant du bullshit qu'ils racontent ? ». Si oui, il s'agit sans doute d'une mode, et alors on peut s'attendre à être envahi de plus en plus par ces conneries. De fait, il faut se procurer un moyen rapide de détecter le bullshit, de pouvoir justifier que ça en est et de pouvoir diffuser l'avertissement. Si les auteurs n'ont pas conscience de la merde qu'ils racontent, alors il faut leur fournir un outil afin qu'il puissent eux-même évaluer de manière factuelle les conneries qu'ils racontent.

## Comment

Ce fichier propose une liste de faits qui permettent d'identifier le bullshit d'un discours. Ce sont des faits, pas des concepts, pour pouvoir être factuellement (de fait) vérifiable. La liste donne une indication, si vous validez aucune entrée, il y a peu de chance que ce que vous racontiez soit du bullshit (ou alors c'est du bullshit subtil, et ça c'est déjà plus classe). De même, si vous vérifiez plein d'entrées, alors il y a une bonne chance que vous racontiez de la merde (mais pas forcément, par exemple si vous avez un article satirique, etc..).

Vous avez une idée en plus, faites une pull-request ou envoyez moi un e-mail avec « [DETECTEUR-BULLSHIT] » au début du sujet (ça me permet de trier rapidement les mails, sinon il risque de passer à la trappe).

## Note

Quand je parle d'article, c'est dans le contexte d'article de blog. Pas dans le cas d'article de journal à comité de lecture.

## La liste

 - Calculez la proportion de termes en langue étrangère (je suppose que le plus souvent, ça sera en anglais). Si cette proportion est élevée, alors il y a des chances que vous racontiez de la merde. 
 - Le sujet de l'article n'est pas clair ou n'a pas lieu d'être
   + L'exemple, écrire un article pour discuter de plusieurs définitions d'un terme n'a pas lieu d'être. C'est complètement inutile : soit il y a une définition admise par tout le monde, et de fait vous enfoncez une porte ouverte, soit il y a plusieurs définitions, et dans ce cas (1) il y a peu de chance que le reste du monde s'accorde grâce à votre article; (2) si on écrit un article contenant un terme ambigü, il convient de définir le terme *dans le cadre de l'article*. Typiquement, dans ce fichier, j'utilise « article » qui a plusieurs compréhensions complètement différentes, et regardez, j'ai mis dans l'intro de quoi exactement (bien qu'informellement) je parle quand j'écris « article ».
 - Combien est-ce qu'il y a d'annecdote ? Une annecdote n'apporte rien au discours (par définition). De fait, le contenu du discours est inclu dans le contenu de l'article sans les annecdotes. Ainsi, si en enlevant les annecdotes, il vous reste trois lignes, alors votre explication tient en 3 lignes, le reste, c'est du bullshit.
   + L'exemple typique: « On a voulu lancer notre projet, alors on est allé en discuter autour d'un verre. ». Pour faire simple, on s'en balance : ça aurait tout aussi bien pu être autour d'un cassoulet, vous auriez pu avoir la même discussion. Ce qui compte est la conclusion de la discussion, pas la discussion en soit.
 - Inverser les priorités : votre article parle de votre projet ? Alors parlez du projet. Si vous parlez d'autre chose (exemple à tout hasard : le plan d'affaire), vous parlez dans le vent, c'est-à-dire, du bullshit. Bah ouai, votre but, c'est de parler du projet (l'objectif), ou du méta-projet (quels sont les projets annexes nécessaire à votre projet) ?
   + Si vous me parlez pendant 5 pages de votre plan d'affaire, j'en déduis que votre projet, c'est de faire de la thune : (1) Soit c'est le cas, et assumez-le (dites-le explicitement « Je voulais faire de l'argent et j'ai pensé à cette problématique. »); (2) soit ce n'est pas le cas, et dans ce cas pourquoi vous perdez du temps à vous poser des questions annexes (si vous parlez thune, il faut le justifier. Ne pas parler de trucs non nécessaire dont on s'en fout, c'est artificiel) ?
 - Est-ce que vous savez de quoi vous parlez ? Si vous répondez oui sans condition, alors vous racontez sans doute de la merde : si vous savez de quoi vous parlez, alors vous devez connaitre les limites de votre connaissance.
   + Exemple typique : l'expert en finance qui parle de Bitcoin et qui explique pourquoi la blockchain est l'avenir de la finance, mais qui ne sais pas ce qu'est une fonction de hachage.
 - N'utilisez pas (trop) d'abbréviations : à chaque première utilisation d'une abbréviation, il convient de la définir (sauf pour celles entrées dans le *langage courant*). De fait, si vous avez une abbréviation que vous n'utilisez qu'une fois, vous ne gagnez pas de la place, vous en perdez.
   + Exemple de bonne abbréviation : « Notre objectif est atteignable de plusieurs manières (e.g.: manière 1) ». En effet, « e.g. » (du latin « exempli gratia ») est une abbréviation du langage courant.
   + Exemple de bonne abbréviation : « Ce fichier est un détecteur de bullshit (abbr. d.b. dans la suite). [ La suite utilise l'abbréviation «d.b.» ] ». On a « abbr. » qui est l'abbréviation d'«abbréviation» (dans le langage courant), et on définit l'abbréviation « d.b. » qui est ensuite réutilisée.
   + Mauvaise utilisation : « Voici notre b.p.. ». C'est quoi « b.p. » ici ?
   + Attention, les abbréviations standardes changent d'une langue à l'autre (et de fait, c'est aussi compté pour le premier point). Pour savoir quelles abbréviations utiliser, il suffit d'ouvrir un dictionnaire.
   + Je ne rentre pas dans les considérations typographiques des abbréviations.
 - Utilisez des mots attractifs
   + E.g.: « Blockchain », « gestion active », « data » (et en particulier sous la forme « la data »), « expert » (vérifiez que vous ayez effectivement affaire à un expert), « 3D », « crypté », « application », « start-up », etc..
 - Est-ce qu'il y a des « formules mathématiques » ? Mauvaise idée, une formule seule n'a aucun sens et aucun interet. Les maths sont un langage comme un autre (voir le 1er point), à ceci pret que l'intuition a été troqué contre la concision. De fait, un papier de math complète le travail (en langage mathématique) avec des explications en langue naturelle : la langue naturelle est subordonnée et ne sert qu'à apporter de l'intuition. Et ce qui est interessant dans un papier de maths, c'est la relation entre deux formules (e.g.: on sait que la formule *F1* n'est vraie que si *F2* est vraie), une formule en soi n'a somme toute que peu d'interet : ce qui compte est montrer une relation.
   + En particulier, définir quelque chose avec une formule est peut-être super classe, mais c'est juste du bullshit. E.g.: je lisais l'autre jour un article (de bullshit) sur le *growth hack*, et l'un des gars interrogé disait *«Growth marketing = créativité × méthode × KPIs »* (notez au passage l'abbréviation et le terme anglais). Ça ne veut juste rien dire... la multiplication est une opération sur les nombres (la plupart du temps, je ne veux pas rentrer dans les détails). Est-ce que la créativité est un nombre ? Est-ce que la méthode (?) est un nombre ? Et dans la suite de l'article, plus aucune notion de math (quand bien même c'en était une). On peut éventuellement comprendre l'idée qui est de dire que le *growth marketing* dépend de la *créativité*, de *méthodes* et de *KPIs* (si l'un est nul, alors il ne peut y avoir de *growth marketing*, de même que *0* est l'élement absorbant de la multiplication), mais voyez que quand on dit ça, on ne définit absolument pas ce qu'est le *growth marketing*, on donne juste quelques conditions. Et pourtant, on a juste reformulé en langue naturelle ce qui était écrit en maths. Bref, cette définition est vide de sens... et vu qu'elle n'est relié à rien, elle est inutile. Dommage que ce soit le point central de l'auteur...
 - Le jeu de langue foireux
   + « Marketing marketé du web marketing »... Même si ça a du sens, à éviter. C'est nul. Point.

## Idées à vérifier

 - Le rapport « problème » / « solution » : combien de fois solution est mentionné par rapport à « problème »
