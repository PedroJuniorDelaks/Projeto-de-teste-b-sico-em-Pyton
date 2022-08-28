# Projeto-de-teste-basico-em-Pyton
Este projeto visa testar um projeto de calculo de média de vendedores. Projeto este desenvolvido através da aula de nível básico do curso da DIO.
<?xml version="1.0"?>
<flowgorithm fileversion="2.11">
    <attributes>
        <attribute name="name" value=""/>
        <attribute name="authors" value="Pedro"/>
        <attribute name="about" value=""/>
        <attribute name="saved" value="2020-11-02 02:14:21 "/>
        <attribute name="created" value="UGVkcm87UEVEUk8tUEM7MjAyMC0xMS0wMjsiMDE6NTA6MTUgIjsyMjUx"/>
        <attribute name="edited" value="UGVkcm87UEVEUk8tUEM7MjAyMC0xMS0wMjsiMDI6MTQ6MjEgIjsxOzIzNTc="/>
    </attributes>
    <function name="Main" type="None" variable="">
        <parameters/>
        <body>
            <declare name="janeiro, fevereiro, mar&#231;o, abril, total" type="Real" array="False" size=""/>
            <declare name="vendedor" type="String" array="False" size=""/>
            <output expression="&quot;Bem vindo, digite o nome do vendedor&quot;" newline="True"/>
            <input variable="vendedor"/>
            <output expression="&quot;Ola&quot;" newline="True"/>
            <output expression="vendedor" newline="True"/>
            <output expression="&quot;Digite suas vendas em janeiro&quot;" newline="True"/>
            <input variable="janeiro"/>
            <output expression="&quot;Digite suas vendas em fevereiro&quot;" newline="True"/>
            <input variable="fevereiro"/>
            <output expression="&quot;Digite suas vendas em mar&#231;o&quot;" newline="True"/>
            <input variable="mar&#231;o"/>
            <output expression="&quot;Digite suas vendas em abril&quot;" newline="True"/>
            <input variable="abril"/>
            <assign variable="total" expression="(janeiro+fevereiro+mar&#231;o+abril)"/>
            <if expression="total&gt;=5000">
                <then>
                    <output expression="&quot;Parabens&quot;" newline="True"/>
                    <output expression="vendedor" newline="True"/>
                    <output expression="&quot;Voc&#234; receber&#225; um bonus de R$ 500,00 reais como pr&#234;mio&quot;" newline="True"/>
                    <output expression="&quot;O valor total de seus ganhos &#233;:&quot;" newline="True"/>
                    <output expression="total+500" newline="True"/>
                </then>
                <else>
                    <output expression="&quot;infelizmente voc&#234; n&#227;o atingiu a meta&quot;" newline="True"/>
                    <output expression="&quot;Mas como pr&#234;mio de consola&#231;&#227;o, voc&#234; ganhar&#225; R$ 100,00&quot;" newline="True"/>
                    <output expression="&quot;Valor total de ganhos &#233; d&#234;:&quot;" newline="True"/>
                    <output expression="total+100" newline="True"/>
                </else>
            </if>
        </body>
    </function>
</flowgorithm>
