# Pistachio Image Classification
This study aims to identify these two types of pistachios, which are frequently grown in Turkey, by classifying them via convolutional neural networks(CNN).
A total of 2148 images were obtained, 1232 of which were Kirmizi pistachios and 916 Siirt pistachios.

In order to determine the most suitable classification model, the most successful model was determined via classification performed by using different CNN architectures.

<table>
<thead>
<tr class="header">
<th>Model</th>
<th>Accuracy</th>
<th>Loss</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>VGG16</td>
<td>0.5661</td>
<td>0.6847</td>
</tr>
<tr class="even">
<td>ResNet50</td>
<td>0.9191</td>
<td>0.2010</td>
</tr>
<tr class="odd">
<td>Xception</td>
<td>0.9866</td>
<td>0.0343</td>
</tr>
</tbody>
</table>

VGG16 Model: It can be said that the model did not perform well during the training process and struggled to accurately distinguish between the classes in the dataset.

ResNet50 Model: These results suggest that ResNet50, with its more complex architecture, outperforms VGG16. The model is better able to learn patterns within the dataset.

Xception Model: These results demonstrate that the Xception model performs the best among the three models, indicating superior learning of patterns within the dataset.
