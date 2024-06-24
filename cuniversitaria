public class ContaUniversitaria extends Conta implements ITaxas {

    public ContaUniversitaria (int numero, Cliente dono, double saldo, double limite) {
        super (numero, dono, saldo, limite);
        setlimite();
    }
    //1000 e 100
    public void setlimite (double limite) {
        if (limite <= 1000 && limite >= 100) {
            super.limite = limite;
            return true;
        } else {
            super.limite = 1000;
            return false;
    }
        public double CalcularTaxas {
            return 0;
        }
}
