public class Alumno {

	private String nombre;
	private String apellido;
	private double nota; 
	
	
	public String getNombre() {
		return nombre;
	}
	public void setNombre(String nombre) {
		this.nombre = nombre;
	}
	public String getApellido() {
		return apellido;
	}
	public void setApellido(String apellido) {
		this.apellido = apellido;
	}
	public double getNota() {
		return nota;
	}
	public void setNota(double nota) {
		this.nota = nota;
	}
	
	
	@Override
	public String toString() {
		return "Alumno [nombre=" + nombre + ", apellido=" + apellido + ", nota=" + nota + "]";
	
}
	
}

public class Principal {

	public static void main(String[] args) {
		
		Operacion op = new Operacion();
		op.recorrerAlumno();

	}

}


public class Principal {

	public static void main(String[] args) {
		
		Operacion op = new Operacion();
		op.recorrerAlumno();

	}

}
