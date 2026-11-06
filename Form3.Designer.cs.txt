namespace EdrichLogincenter4u
{
    partial class Form3
    {
        /// <summary>
        /// Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        /// Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        /// Required method for Designer support - do not modify
        /// the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            label1 = new Label();
            Dashboard = new GroupBox();
            Dashboard.SuspendLayout();
            SuspendLayout();
            // 
            // label1
            // 
            label1.AutoSize = true;
            label1.Font = new Font("Trebuchet MS", 24F, FontStyle.Italic, GraphicsUnit.Point, 0);
            label1.Location = new Point(18, 15);
            label1.Name = "label1";
            label1.Size = new Size(168, 40);
            label1.TabIndex = 0;
            label1.Text = "Dashboard";
            label1.Click += label1_Click;
            // 
            // Dashboard
            // 
            Dashboard.Controls.Add(label1);
            Dashboard.Location = new Point(34, 19);
            Dashboard.Name = "Dashboard";
            Dashboard.Size = new Size(1138, 625);
            Dashboard.TabIndex = 1;
            Dashboard.TabStop = false;
            Dashboard.Text = "Dashboard";
            // 
            // Form3
            // 
            AutoScaleDimensions = new SizeF(7F, 15F);
            AutoScaleMode = AutoScaleMode.Font;
            ClientSize = new Size(1188, 789);
            Controls.Add(Dashboard);
            ForeColor = SystemColors.Highlight;
            Name = "Form3";
            Text = "Form3";
            Dashboard.ResumeLayout(false);
            Dashboard.PerformLayout();
            ResumeLayout(false);
        }

        #endregion

        private Label label1;
        private GroupBox Dashboard;
    }
}