# DO - PRODUCT-CARD

Este es un paquete de pruebas de despliegue en NPM 


### Carlos Ortega

## EJemplo
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'do-produc-card'
```

```
        <ProductCard 
            product={ product }
            initialValues={{
              count: 4,
              // maxCount: 10,
            }}
        >

          {
            ( { reset, count, increaseBy, isMaxCountReached, maxCount } ) => (
              <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />              
              </>
            )
          }
        </ProductCard>
```