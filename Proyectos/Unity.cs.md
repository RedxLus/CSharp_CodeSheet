public float velocidad;
public float distancia = 20f;
public float tiempo = 1f;

void Update() {

if(Input.GetKeyDown(KeyCode.Space)) {
ComprobarVelocidad ()
}

}

void ComprobarVelocidad () {

velocidad = distancia / tiempo;
print("Tu velocidad es:" + velocidad );


}
