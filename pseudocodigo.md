
class Sucursal {

    float gananciasDeHoy;
    int ventasTotales;
    TotalPorDia gananciasPorDia = new TotalPorDia[];

    void vender(prendas) {
        // actualiza ganancia y ventasTotales
    }

    gananciasDe(fecha) {
        // actualiza gananciasPorDia   
    }
}

class TotalDelDia {

    float total;
    Date fecha;
}

class Prenda {

    string tipo;
    float precioBase;
    string estado;

    float precioFinal() {
        // calcula precio segun precioBase y estado
    }
}

class Venta {

    Prenda prendas = new Prendas[];
    Date fecha = new Date();
    MedioDePago medioDePago;

    float total() {
        //suma precios de cada prenda segun medioDePago
    }
}

class MedioDePago {

    int montoDisponible;
}

class Efectivo extends MedioDePago {

}

class TarjetaDeCredito extends MedioDePago {

    int cantidadCuotas;
    int recargoFijo;

    float recargoFinal() {
        // calcula recargo
    }
}

Anotaciones:
- Supongo que las prendas no pueden tener mas de un estado al mismo tiempo
- Los metodos no están implementados, solo se describe su tarea