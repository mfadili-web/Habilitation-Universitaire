# Habilitation-Universitaire
## Controllability of some Deterministic and Stochastic Systems of Parabolic Equations
Ce mémoire de l’habilitation à diriger des recherches est l’occasion d’exposer
mon parcours d’enseignant-chercheur à l'école normale supérieure université Cadi Ayyad et de la mise en valeur des missions qui m'ont été confiées au sein du ministère de l'éducation nationale avant 
mon concours de professeur assistant.\\

Mon axe de recherche est toujours l'étude de la contrôlabilité des systèmes d'équations couplés. En effet, nous considérons le système parabolique a $n$ équations dégénérées soumis a $m$ contrôles
	\begin{equation}\label{systeme1}\tag{I}
	\begin{cases}
		\partial_ty-D\mathcal{M}y+Ay=Bv  \mathbbm{1}_{\omega}\quad\text{ in } Q_T,\\
	%¨	\ds d_t z+\left(a(x) z_x\right)_x dt +b z(t,x)dt +c k dt= \mathbbm{1}_{\omega}v dt +kdW(t) \quad\text{ in } Q_T,\\
		C y=0,\qquad \text{ on } \Sigma_T ,\\
		y(0,\cdot)=y_0, \qquad \text{ in} (0,1),  
	\end{cases}
\end{equation}
où $D$ est la matrice de diffusion, $A$ matrice de couplage, $B$ est la matrice de contrôle et $\mathcal{M}$ est l’opérateur différentiel défini par $\mathcal{M} y = (a(x)y_x)_x$.
 	
Au cours de ma thèse de doctorat, nous avons traité la contrôlabilité du système \eqref{systeme1} dans les cas suivants:\\
$\bullet$ le cas d’un système cascade soumis à plusieurs contrôles et une matrice de diffusion de la forme $D=diag(d_1,\cdots,d_n)$ avec ($di>0$) voir \cite{FadMan}.\\
$\bullet$ le cas d’un système complet où la matrice de diffusion $D = d.I_n$, nous avons montré que la condition algébrique de Kalman $rank[A|B] = n $ caractérise la contrôlabilité à zéro du système \eqref{systeme1} Voir \cite{benfama}.\\

Dans le présent travail nous nous intéressons au cas ou la matrice de diffusion $D$ n'est pas diagonalisable, nous montrons également si la condition algébrique de Kalman $rank[A|B] = n$ est satisfait par les deux matrices de couplage $A$ et de contrôle  $B$ le système \eqref{systeme1} est contrôlable à zéro (voir la sous-section \ref{hadahada1} et  \cite{benfama1}).\\


Passant maintenant dans le contexte stochastique, ou nous considérons le systèmes des équations stochastiques rétrogrades couplées suivantes 

\begin{equation}\label{equ:1.1}\tag{II}
	\begin{cases}
		\ds d_t y_1= \left[-\Delta y_1+\sum_{i=1}^{m}a_{1 i}y_i +c_1 Y_1 +\mathbbm{1}_{G} v\right]dt+ Y_1dW(t),\\
		\ds d_t y_2= \left[-\Delta y_2+\sum_{i=1}^{m}a_{2 i}y_i +c_2 Y_2 \right]dt+ Y_2dW(t),\\
		\qquad\qquad \hspace*{2.5cm}\vdots	\hspace*{4.5cm} \quad\text{ in } Q \\
		\ds d_t y_m= \left[-\Delta y_m+\sum_{i=1}^{m}a_{m i}y_i +c_m Y_m \right]dt+ Y_mdW(t),\\	
		y_i=0\quad 1\leq i\leq m \hspace*{5.5cm} \text{ on } \Sigma ,\\
		y_i(T,\cdot)=y_{i T}(\cdot) \quad 1\leq i\leq m \quad \hspace*{4cm} \text{ in } \mathcal{D},  
	\end{cases}
\end{equation}
où $(y_i,Y_i)$ est la variable d'état de la $i$-ième équations.\\
Nous montrons si la première  matrice de couplage est triangulaire supérieure avec une sous diagonale non nul, alors le système \eqref{equ:1.1} peut être contrôlé avec un seul en utilisant un seul contrôle (voir la sous-section \ref{hadahada2} et  \cite{fadili}).\\


Et finalement l'objet du troisième papier est l'étude du problème stochastique rétrograde suivant 
\begin{equation}\label{equIII}\tag{III}
	\begin{cases}
		\ds d_t y_1= \left[-\Delta y_1 +a_1y_1+c_{1,1} Y_1 +c_{1,2} Y_2+\mathbbm{1}_{G} v\right]dt+ Y_1dW(t), \hspace*{.5cm} \quad\text{ in } Q\\
		\ds d_t y_2= \left[-\Delta y_2+a_2y_2+c_{2,1} Y_1 +c_{2,2} Y_2 \right]dt+ Y_2dW(t),\hspace*{.5cm} \quad\text{ in } Q\\
		%	\qquad\qquad \vdots	\hspace*{6.5cm} \quad\text{ in } Q \\
		%	\ds d_t y_m= \left[-\Delta y_m+\sum_{i=1}^{m}a_{m i}y_i +c_1 Y_m \right]dt+ Y_mdW(t),\\	
		y_i=0\quad  i\in \{1,2\} \hspace*{5.5cm} \text{ on } \Sigma ,\\
		y_i(T,\cdot)=y_{i T}(\cdot)\quad i\in \{1,2\} \quad \hspace*{4cm} \text{ in } \mathcal{D},  
	\end{cases}
\end{equation}
où les deux équations sont couplés uniquement a l'aide de leurs seconde variables d'état. La condition suivante 
\begin{equation}\label{C_condition}
	c_{2 1} \geqslant c>0 \, \text{ or } 	-c_{2 1} \geqslant c>0 \,\,\text{ in } \, G_0\times(0,T).
\end{equation}
sur la seconde matrice de couplage nous permet de prouver la contrôlabilité à zéro du système \eqref{equIII} sous l'action d'un seul contrôle (voir la sous-section \ref{hadahada3} et  \cite{fadiliManiar}). \\
Ce mémoire est présenté comme suit : section 2 est dédié à mon curriculum vitae. Section 3 est consacré à mes récents travaux de recherches. Dans la section 4 je présente mon parcours professionnel est pédagogique et enfin je conclus ce travail par quelques perspectives. 
