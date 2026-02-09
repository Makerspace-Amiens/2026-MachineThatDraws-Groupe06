# Documentation Technique

## ⚙️ Fonctionnement de la machine
La machine utilise deux axes (X et Y) pour déplacer le stylo sur la surface. Un troisième mécanisme (souvent un servo-moteur) permet de lever et baisser le stylo.

## 💻 Partie Logicielle
Voici la structure de base du code de test pour vérifier les mouvements de la machine :

```cpp
// Exemple de test de mouvement
void setup() {
  pinMode(13, OUTPUT); // Initialise la broche pour les tests
}

void loop() {
  digitalWrite(13, HIGH); // Allume
  delay(1000);
  digitalWrite(13, LOW);  // Éteint
  delay(1000);
}
