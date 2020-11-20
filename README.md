# Projeto-site
Site criado com utilização de bootstrap 

titulo_noticias = dataset.sample(100).orgao.values 
#teste_ = titulo_noticias.sample(50)
#print(titulo_noticias)

plt.title('Modelo melhorado') 

labels = 'area médica', 'Área assistencial', 'Área administrativa','Residência médica','Residência multiprofissional'
sizes = [' {}'.format(metrics.accuracy_score(classes, resultados_)),' {}'.format(metrics.accuracy_score(classes1, resultados_1)),' {}'.format(metrics.accuracy_score(classes2, resultados_2)), 
        ' {}'.format(metrics.accuracy_score(classes3, resultados_3)),' {}'.format(metrics.accuracy_score(classes4, resultados_4))]
colors = ['lightskyblue','yellow','yellowgreen','gray','red']
explode = (0,0,0,0,0) # afasta o setor
plt.pie(sizes, explode=explode,labels=labels,autopct='%1.1f%%',colors=colors)
plt.axis('equal')
plt.show()

