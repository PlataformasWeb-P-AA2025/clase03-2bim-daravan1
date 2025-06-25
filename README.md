# clase03-2bim

## Explicación Codigo

![WhatsApp Image 2025-06-18 at 8 11 19 AM](https://github.com/user-attachments/assets/39925ff6-d794-4b01-94ec-d43903e282e4)  

Cuando no se encuentra en los modelos la relación con relate_name se puede seguir usando la relación inversa a través del _set.all extrayendo todos los objetos. Si no se le da un nombre personalizado lo genera de forma automatica.

### 25 junio 2025

* Se agrega un número telefonico a un estudiante especifico. Para esto se llama a la clase NumeroTelefonicoEstudianteForm(ModelForm) 
que recibe un objeto de tipo estudiante, gracias a un init se obtienen los atributos del objeto y se esconde en el formulario el ingreso de datos gracias a un forms.widgets.HiddenInput() para que esos atributos no sean modificados al ingresar un nuevo número.