   ___                 _                     _            
  / __\ ___  _ __ ___ | |__   ___ _ __ /\/\ (_)_ __   ___ 
 /__\/// _ \| '_ ` _ \| '_ \ / _ \ '__/    \| | '_ \ / _ \
/ \/  \ (_) | | | | | | |_) |  __/ | / /\/\ \ | | | |  __/
\_____/\___/|_| |_| |_|_.__/ \___|_| \/    \/_|_| |_|\___|



@author:	Pascal Reminy, J�r�mie Ferreira
@description:	@see GameDocBomberMine.docx
@feaures:
	-param�trage client/serveur ind�pendant du build
	-2 joueurs d�pla�ables
	-Bombes et mines impl�ment�es sans composante r�seau encore et sans pouvoir �tre directement utilis�es par le joueur (elles sont plac�es dans le niveau pour l'instant)

@warning:	L'alpha que nous avons envoy� a un probl�me dans sa configuration r�seau, nous avons r�solu ces probl�mes apr�s le rendu et pour ne pas tout renvoyer, nous vous envoyons une 2nde build "CorrectedBuild.exe". Les modifications op�r�es sont les suivantes :
	-suppression des NetworkViews des joueurs
	-sur le NetworkView de l'empty Network : StateSync pass� � Unreliable et Oberved pass� � None

@QuickNote: les d�placements se font avec ZQSD et la direction est reprise de la vue du joueur.






