# Analogía con la polarización de la luz.

Dado que esta situación es nueva, podemos buscar alguna analogía con algún fenómeno físico ya conocido. Por esta razón,  discutiremos algunos aspectos sobre la polarización de la luz.

Consideraciones:

1. Supongamos que tenemos una **onda de luz polarizada** que se **propaga en la dirección z**.
2. Luz x-plolarizada:
    
    $\mathbf{E} = E_o \hat{\mathbf{x}} cos(kz-\omega t)$.
    
3. Luz y-polarizada:
    
    $\mathbf{E} = E_o \hat{\mathbf{y}} cos(kz-\omega t)$.

   AJAM

# 📚 Definiciones: Variedades Diferenciables

---

## 🔹 Lista de Definiciones

**Variedad diferenciable**  
: Un ==espacio== topológico $M$ que es Hausdorff, segundo numerable, y localmente homeomorfo a $\mathbb{R}^n$.  
  Además, existe un **atlas diferenciable** $\mathcal{A} = \{ (U_\alpha, \varphi_\alpha) \}$ tal que las funciones de cambio de coordenadas
  $$
  \varphi_\beta \circ \varphi_\alpha^{-1} : \varphi_\alpha(U_\alpha \cap U_\beta) \subseteq \mathbb{R}^n \to \varphi_\beta(U_\alpha \cap U_\beta) \subseteq \mathbb{R}^n
  $$
  son de clase $C^\infty$.

**Carta (chart)**  
: Un par $(U, \varphi)$ donde $U \subseteq M$ es abierto y $\varphi : U \to \mathbb{R}^n$ es un homeomorfismo sobre su imagen.  

**Atlas**  
: Una colección de cartas $\{ (U_\alpha, \varphi_\alpha) \}$ que cubren $M$, es decir:  
  $$
  M = \bigcup_\alpha U_\alpha
  $$

**Función diferenciable en $M$**  
: Una aplicación $f : M \to \mathbb{R}$ es diferenciable en $p \in M$ si para alguna carta $(U, \varphi)$ con $p \in U$, la composición
  $$
  f \circ \varphi^{-1} : \varphi(U) \subseteq \mathbb{R}^n \to \mathbb{R}
  $$
  es diferenciable en el sentido usual.  

---

📌 **Ejemplo**: La esfera $S^2 \subset \mathbb{R}^3$ es una variedad diferenciable de dimensión $2$, con atlas dado por las proyecciones estereográficas desde los polos norte y sur.  

