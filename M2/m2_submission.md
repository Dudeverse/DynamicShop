<table><tr><td> <em>Assignment: </em> M2 Python-HW</td></tr>
<tr><td> <em>Student: </em> Surya Teja Ethalapaka (se352)</td></tr>
<tr><td> <em>Generated: </em> 9/25/2022 1:27:40 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-005-F22/m2-python-hw/grade/se352" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <p>Make sure you have the dev/prod branches created before starting this assignment.</p><p>Pre-req Steps if not done so yet:</p><p><ol><li>git checkout main</li><li>git checkout -b dev</li><li>git push origin dev</li><li>git checkout -b prod</li><li>git push origin prod</li></ol><div>This will ensure you have a dev and prod branch on github.</div></p><p>Setup steps:</p><ol><li><code>git checkout dev</code></li><li><code>git pull origin dev</code></li><li><code>git checkout -b M2-Python-HW</code></li></ol><p>You'll have 3 problems to save for this assignment.</p><p>Each problem you're given a template&nbsp;<strong>Do not edit anything in the template except where the comments tell you to</strong>.</p><p>The templates are done in such a way to make it easier to capture the output in a screenshot (if it's still not able to fit well, you can zoom out in your browser).</p><p>You'll copy each template into their own separate .py files, immediately git add, git commit these files (you can do it together) so we can capture the difference/changes between the templates and your additions. This part is required for full credit.</p><p>HW steps:</p><ol><li>Open your IDE at the root of your repository folder</li><li>In your IDE create a new folder/directory called M2</li><li>Create 3 new files in this new M2 folder (problem1.py, problem2.py, problem3.py)</li><li>Paste each template into their respective files</li><li><code>git add .</code></li><li><code>git commit -m "adding template baselines</code></li><li>Do the related work (you may do steps 8 and 9 as often as needed or you can do it all at once at the end)</li><li><code>git add .</code></li><li><code>git commit -m "completed hw"</code></li><li>When you're done push the branch<ol><li><code>git push origin M2-Python-HW</code></li></ol></li><li>Create the Pull Request with&nbsp;<strong>dev</strong>&nbsp;as base and&nbsp;<strong>M2-Python-HW</strong>&nbsp;as compare</li><li>Create a new file in the M2 folder in your IDE called m2_submission.md</li><li>Fill out the below deliverable items, save the submission, and copy to markdown<ol><li>For this assignment you may get screenshots from your IDE output or terminal/console output</li></ol></li><li>Paste the markdown into the m2_submission.md</li><li>add/commit/push the md file<ol><li><code>git add m2_submission.md</code></li><li><code>git commit -m "adding submission file"</code></li><li><code>git push origin M2-Python-HW</code></li></ol></li><li>Merge the pull request from step 11</li><li>On your local machine sync the changes<ol><li><code>git checkout dev</code></li><li><code>git pull origin dev</code></li></ol></li><li>Make a pull request from&nbsp;<strong>prod</strong>&nbsp;as base and&nbsp;<strong>dev</strong>&nbsp;as compare and immediately merge it</li><li>Submit the link to the m2_submission.md file from the prod branch to Canvas</li></ol><p><strong>Template Files</strong>&nbsp;You can find all 3 template files in this gist:&nbsp;<a href="https://gist.github.com/MattToegel/3c55ca7bb631ff6f492bf6f1ad27270e">https://gist.github.com/MattToegel/3c55ca7bb631ff6f492bf6f1ad27270e</a></p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Problem 1 - Only output Odd values of the Array under "Odds output" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Clearly screenshot the output of Problem 1 showing the data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/107896500/192155611-058ae7db-2703-49b7-b0a4-04c1cf94069d.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Output showing odd values in the lists provided<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>I have used list comprehension to get the values in the lists that<br>are odd. In line 11, I have created a list that contains the<br>elements iterated across the length of the list which finds out if an<br>element is not divisible by 2. If such element exists, then it is<br>added into Odds_list. Then I printed the Odds_list to screen.<div><br></div><div>Comprehensions: I have learnt<br>about comprehensions about a year ago while learning python for the first time.<br>Comprehensions use very less syntax. It helps us to use variables minimally. In<br>my opinion, Python code is almost like writing in English and comprehensions is<br>also just like writing a passage of meaningful sentences. Once we get the<br>hang of it, comprehensions are easy to use.&nbsp;</div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Problem 2 - Only output the sum/total of the list values by assigning it to the 'total' variable (the number must end in 2 decimal places, if it ends in 1 it must have a 0 at the end) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Clearly screenshot the output of Problem 2 showing the data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/107896500/192155729-d8fcd89a-d941-4c8d-a937-49de581a38bc.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The screenshot shows the sum of the values in each list and also<br>rounded off to two decimal places.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>In line 12, I used the in-built sum method of python to get<br>the sum of the values in the list. And for the solution of<br>always rounding to two decimal places, I have used the {:.2f}&nbsp;<div>in the formatted<br>string. using {:.3f} would round it off to 3 decimal places and so<br>on. (From zybooks lessons)</div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Problem 3 - Output the given values as positive under the "Positive Output" message (the data otherwise shouldn't change) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Clearly screenshot the output of Problem 3 showing the data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/107896500/192155805-1b618b35-8ecd-4de2-9899-8826e6412883.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The screenshot shows processed arrays that have positive values of the input arrays.<br>The output is in this format : [ value1, type1, value2 , type2<br>... and so on.] .<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Describe how you solved the problem</td></tr>
<tr><td> <em>Response:</em> <p>Depending upon the type of values in the list, I changed the operation<br>on the list.<div>Say if the type of values are int in a list,<br>all I had to do was to negate the negative values and append<br>them to a new list. While the positive values are kept the same<br>and also appended to the new list.&nbsp;</div><div>The new list would contain values that<br>are all positive now.</div><div><br></div><div>The same logic applies for float.</div><div><br></div><div>While handling the string data<br>type, I have changed the value type to int and then proceeded to<br>negate them, in case they&#39;re negative. Then I added them to a new<br>list If the type was positive, I kept them as is and updated<br>the new list. Just before adding them to the new list, I have<br>changed the type of the value to str back again.</div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc Items </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Pull Request URL for M2-Python-HW to dev</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Dudeverse/IS601-005/pull/3">https://github.com/Dudeverse/IS601-005/pull/3</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Talk about what you learned, any issues you had, how you resolve them</td></tr>
<tr><td> <em>Response:</em> <div>1. I have learnt the different methods to handle lists using functions and<br>loops.</div><div>2. Learnt how to manipulate strings and also floating point numbers.</div><div>3. Learnt how<br>to use operators, importantly the modulo operator.</div><div>4. Learnt how to write code neatly.<br>Using single spaces before and after operators is the trick.&nbsp;</div><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-005-F22/m2-python-hw/grade/se352" target="_blank">Grading</a></td></tr></table>