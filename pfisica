
import java.util.Date;
import java.util.Objects;

public class PessoaFisica extends Cliente implements ITaxas{

    private String cpf;

    private int idade;

    private char genero;

    public PessoaFisica(String nome, String endereco, Date data, String cpf, int idade, char genero) {
        super(nome, endereco, data);
        this.cpf = cpf;
        this.idade = idade;
        this.genero = genero;
    }

    public double CalcularTaxas {
        return 10;
    }
    public String toString() {
        return "cpf=" + cpf + '\n' +
                "idade=" + idade + '\n' +
                "genero=" + genero;
    }

    public boolean equals(Object o) {
        if (this == o) return true;
        if(o instanceof PessoaFisica) {
            PessoaFisica pessoa = (PessoaFisica) o;
            return Objects.equals(cpf, pessoa.cpf);
        }
        return false;
    }

    public abstract boolean autenticar(String chave) {
        if (chave.equals(this.cpf)) {
            return true;
        } else {
            return false;
        }
    }
}
