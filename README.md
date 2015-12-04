# deberes-y-ejercicio-en-clase
realizado en eclipse 

package poo1;

public class Circulo {
        private double Radio;
       
        public Circulo(){
       
        }
           public void setRadio(double RadioParam){
        		this.Radio = RadioParam;
        	}
        	public double getRadio(){
        		return this.Radio;
        	}
        	public Circulo (double RadioParam){
        		this.Radio = RadioParam;
        }
        	public double getArea(){
        		return Math.PI * Radio * Radio;
        	}   
       
    }
